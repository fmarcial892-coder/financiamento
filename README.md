# Financiamento BV — Site estático

Site estático em HTML, publicado a partir de `financiamentobv/`.

## Render

Configuração versionada em `render.yaml`:
- runtime: static
- publicação: `financiamentobv`
- rewrite: `/*` → `/index.html`

Isso permite abrir a página mesmo em rotas como `/debug` sem retornar 404.

O projeto não usa Docker, Node.js ou dependências de build.
