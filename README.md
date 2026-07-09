# Lembrou

App PWA simples para controle pessoal de medicamentos, refeições, tarefas, anotações e hábitos.

## Como subir no GitHub Pages

1. Crie um repositório no GitHub.
2. Faça upload de todos os arquivos deste pacote na raiz do repositório.
3. Vá em **Settings > Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**.
5. Selecione a branch `main` e a pasta `/root`.
6. Salve e aguarde o link do GitHub Pages aparecer.

## Arquivos principais

- `index.html`: aplicativo.
- `manifest.webmanifest`: configuração para instalar como app/PWA.
- `sw.js`: service worker para cache básico.
- `icon-192.png`, `icon-512.png`, `apple-touch-icon.png`: ícones do app.

Os dados ficam salvos no navegador pelo `localStorage`.
