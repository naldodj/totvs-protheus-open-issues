# TOTVS Protheus Open Issues

> "A gente não quer desrespeitar o sistema. A gente quer que ele funcione."

## 💡 Sobre

Este repositório é uma iniciativa independente da comunidade técnica que trabalha diariamente com o **TOTVS Protheus**, com o objetivo de:

* Documentar erros reais encontrados no sistema
* Compartilhar soluções alternativas ou *workarounds*
* Rastrear quais problemas já foram resolvidos (e em qual build)
* Facilitar a colaboração entre devs, consultores e integradores
* Dar visibilidade a pontos críticos ignorados por canais oficiais

Se você ama o Protheus como a gente, se quer ver ele brilhar como o melhor sistema ERP do Brasil e do mundo, com a nossa cara, com a nossa força — então que tal contribuir?

📌 Comente, documente, sugira, reporte, compartilhe contornos e soluções. Aqui é espaço de construção coletiva.

## ❗ Por que isso existe?

Porque, infelizmente, muitos erros são recorrentes, mal documentados e ignorados nos chamados abertos na TOTVS — quando conseguimos abrir um.

Este projeto **não tem o objetivo de denegrir** a TOTVS, nem o Protheus, mas sim **de cobrar melhorias, com base em fatos e respeito à comunidade que faz esse ecossistema girar**.

Somos todos BR. E queremos um Protheus mais forte, mais justo e mais funcional para as empresas brasileiras.

> **Não é crítica. É manutenção. É evolução.**

## 📌 Como contribuir

1. Clone o repositório
2. Crie um arquivo `.md` na pasta `issues/` com o nome do módulo ou erro
3. Descreva:

   * O problema
   * Passos para reproduzir
   * Build testada
   * Logs ou prints (se possível)
   * *Workaround* (se houver)
4. Faça um pull request

Exemplo:

```markdown
# Erro: REST MPP ignora JWT vindo de domínio externo

## Descrição
Quando configurado com ExternalURL apontando para um domínio externo, o Protheus REST não valida corretamente tokens JWT emitidos pelo próprio fluxo OAuth2.

## Build
7.00.240223P-20250326

## Logs
type mismatch on + on TLPP.REST.AUTHENTICATION.OAUTH2TOKEN line : 51

## Workaround
Reescrever handler TLPP para validar manualmente o token ou usar Basic Auth.
```

## 📣 TOTVS, se você está lendo isso...

Interagir com a comunidade **não é fraqueza. É visão.**

Estamos aqui porque **acreditamos** no potencial do Protheus. E é exatamente por isso que reportamos o que está quebrado.

Ajude-nos a construir um Protheus cada vez melhor, mais estável e mais alinhado com as necessidades reais da comunidade técnica.

## 🧹 Licença

MIT — porque conhecimento bom é conhecimento livre.

---

> **BR que é BR reporta bug com CPF na nota.**
