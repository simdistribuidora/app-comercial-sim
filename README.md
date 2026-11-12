# SIM Comercial — atalho do app

Esta página é **só o atalho** (link curto + ícone) do App Comercial SIM. Nenhum dado fica aqui.
O app roda no Apps Script da SIM e o login é a conta Google da SIM.

- `index.html`: página com o botão "Abrir o app" e as instruções para pôr o ícone na tela inicial.
  Aberta pelo ícone (endereço com `?abrir=1`), vai direto para o app.
- **Destino:** linha `var DESTINO = ...` do `index.html`. Se a implantação do Apps Script mudar, troque só essa linha.
- `manifest.webmanifest`, `icon-*.png`, `apple-touch-icon.png`, `logo.webp`: nome e ícone na tela inicial.
