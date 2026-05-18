# Big Compra Vision PWA

Este diretorio contem um snapshot do app publicado em `https://big-compra-vision.lovable.app/`, ajustado para funcionar como PWA em hospedagem estatica.

## O que foi adicionado

- `manifest.webmanifest`
- `service-worker.js`
- icones para instalacao
- caminhos relativos para funcionar em GitHub Pages
- `404.html` para fallback de SPA

## Observacoes

- Este pacote foi montado a partir do build publicado, nao do projeto-fonte do Lovable.
- O JavaScript publicado faz referencia a Supabase, entao a aplicacao pode depender de servicos externos ja configurados.
- O caminho oficial e mais seguro continua sendo exportar o projeto pelo proprio Lovable para o GitHub.
