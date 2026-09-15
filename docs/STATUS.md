# STATUS — Integrador Bling → ERP (demonstração)

> Atualizado: 2026-09-15

## O que é

**Demonstração de interface**, não o integrador. Uma tela única que mostra como seria o
acompanhamento e a revisão dos pedidos que vêm do Bling: fila do que travou, cartão de revisão,
contagem e alerta.

Os dados na tela são **de exemplo** — o app não fala com banco, não tem Supabase e não tem
back-end. Não copie daqui número, status ou nome de cliente como se fosse real.

## Onde está

- **Clone nesta máquina (`ecommerce06`):** `C:\Aplicações da bononi\integrador-demo`.
- **Remote:** `leobononi2906/integrador-demo`, branch `main`.
- **Conteúdo:** um `index.html` (~16 KB). Sem build, sem dependência, sem deploy configurado.
- **Fontes por CDN** (Google Fonts: IBM Plex Sans e Mono) — é protótipo, então não há o cuidado
  de PWA offline que os apps de verdade têm.

## O integrador de verdade

Este repo **não** é a implementação. O que existe sobre o assunto:

| Onde | O que tem |
|---|---|
| `bononi-integrador/docs/STATUS.md` | o projeto real: as três frentes, os contratos de webhook, o financeiro de marketplace, o que trava |
| `bononi-exped/docs/INTEGRACAO_BLING.md` | a cadeia Bling → SGA/Integra → apps em produção, e o runbook de "parou de trazer pedido" |
| Hub, aba Integrador | a tela que a operação usa de fato (5 subabas) — ver `bononi-hub/docs/ARQUITETURA.md` §Integrador |

## Pendências / próximos passos

- Nada em andamento. É material de apresentação; só mexer se houver nova rodada de alinhamento
  com a equipe do ERP.
- Se o pedido for "fazer funcionar de verdade", **não é alteração aqui** — é o projeto do
  `bononi-integrador`, e a conversa passa pela cadeia real do Bling.

## Dívidas e armadilhas conhecidas

- **Protótipo que parece produto.** A tela é convincente o suficiente para alguém achar que o
  integrador já existe assim. Ao mostrar, dizer que é demonstração.
- Sem versionamento de assets nem cache-buster: se um dia isso for publicado em algum lugar,
  vale ler a skill `publicar-e-conferir` antes.

## Dev-log

- 2026-09-15 — **`docs/STATUS.md` e `CLAUDE.md` criados.** O repo não tinha índice nenhum, o que
  fazia dele o único do grupo invisível para quem chegasse pelo padrão de documentação. Nada de
  código foi alterado. Registrado também que é demonstração, porque a tela não deixa isso óbvio.
