# Painel do Fígado

Página única (`public/index.html`) para registrar exames do fígado por data, com ilustração que muda de cor, gráfico de evolução e histórico.

- Os dados ficam só no navegador de cada pessoa. Nada é enviado a servidor.
- Publicado no Cloudflare como site de arquivos estáticos (`wrangler.jsonc`).
- Para alterar o painel, edite `public/index.html`. Cada envio ao repositório republica o site.
