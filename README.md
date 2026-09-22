# Estúdio Focos - Clone Exato

Clone completo e fiel do site [https://preview-2-kappa.vercel.app/](https://preview-2-kappa.vercel.app/).

## Estrutura do Projeto

- `index.html`: Página principal com todo o conteúdo original, meta tags, schemas e estrutura semântica.
- `privacidade/index.html` (e `privacidade.html`): Página de política de privacidade.
- `termos/index.html` (e `termos.html`): Página de termos de uso.
- `_next/`:
  - `static/immutable/chunks/`: Bundles JavaScript e CSS de estilo idênticos aos de produção.
  - `static/immutable/media/`: Todas as fontes Manrope originais em formatos WOFF e WOFF2.
- `images/`:
  - `camera-poster.svg`, `og-estudio-focos.svg` e `marcelo-ribeiro.png`.
  - `portfolio/`: Todas as fotografias originais em alta resolução.
- `favicon.svg`: Ícone do site.
- `server.js`: Servidor HTTP leve em Node.js (sem dependências externas) com suporte automático ao endpoint `/_next/image` e roteamento limpo.

## Como Executar

Para iniciar o servidor localmente:

```bash
npm start
```
ou
```bash
node server.js
```

Abra no seu navegador o endereço indicado (ex: `http://localhost:3000/` ou `http://localhost:3001/`).
