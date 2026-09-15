# Integrador Bling → ERP (integrador-demo) — guia do projeto

> Contexto do grupo e regras de banco: skill `bononi-contexto`.

## O que é

**Demonstração de interface** do Integrador Bling → ERP: uma tela única que mostra como seria o
acompanhamento e a revisão dos pedidos que vêm do Bling.

**Não é o integrador.** Não fala com banco, não tem Supabase, não tem back-end — os dados na tela
são de exemplo. O integrador de verdade é outra coisa, e a cadeia Bling → SGA/Integra → apps está
documentada em `bononi-exped/docs/INTEGRACAO_BLING.md`.

## Onde está

- **Clone nesta máquina (`ecommerce06`):** `C:\Aplicações da bononi\integrador-demo`.
- **Remote:** `leobononi2906/integrador-demo`, branch `main`.
- **Conteúdo:** um `index.html` (~16 KB). Sem build, sem dependência, sem `docs/`.

## Ao mexer aqui

- É protótipo: vale otimizar para ficar **claro na demonstração**, não para virar produção.
- Se o pedido for "fazer funcionar de verdade", isso não é uma alteração neste arquivo — é
  projeto novo, e a conversa passa pela cadeia real do Bling. Vale perguntar antes de começar.
- Não copie daqui número, status ou nome de cliente como se fosse dado real: é tudo fictício.
