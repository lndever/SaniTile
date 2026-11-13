# SaniTile — Site de Apresentação

Site institucional do produto **SaniTile**, piso modular drenante, desenvolvido para a Feira da ETEC (Administração).

## Como visualizar

Abra o arquivo `index.html` no navegador (Chrome, Edge, Firefox etc.).

## Como publicar no GitHub Pages

1. Crie um repositório no GitHub (ex: `sanitile` ou `sanitile-site`).
2. Faça o upload destes arquivos (ou use `git`):
   ```bash
   git init
   git add .
   git commit -m "Site SaniTile - Feira ETEC"
   git branch -M main
   git remote add origin https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git
   git push -u origin main
   ```
3. No GitHub, vá em **Settings → Pages**.
4. Em **Source**, escolha a branch `main` e a pasta `/ (root)`.
5. Salve. Em alguns minutos o site estará no ar em:
   `https://SEU-USUARIO.github.io/SEU-REPOSITORIO/`

## Estrutura

- `index.html` — Página completa do site (única página necessária)

## Cores utilizadas

- Verde principal: `#1B5E20`
- Verde claro: `#2E7D32`
- Preto: `#0A0A0A` / `#121212`
- Branco: detalhes e textos

## Observação

O site é 100% estático (HTML + CSS + um pouco de JavaScript). Não precisa de servidor ou instalação de nada para funcionar.
