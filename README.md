# Playbook Provecta VGV · Formulários Instantâneos

Site estático (sem build). Arquivos:

- `index.html`: playbook interativo, autocontido
- `playbook-provecta-vgv.pdf`: versão PDF interativa (botão "Baixar PDF interativo")
- `og-image.png`: capa exibida ao compartilhar o link
- `vercel.json`: força o download do PDF

## Publicar na Vercel
1. Importe este repositório em vercel.com/new
2. Framework Preset: **Other**. Build Command e Output Directory: deixe em branco
3. Deploy

Se o domínio final for diferente de `playbook-formul-rios-provecta-vgv.vercel.app`, troque esse endereço nas tags `og:url` e `og:image` do `index.html`.
