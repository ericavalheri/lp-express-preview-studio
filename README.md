# LP Express Studio Standalone

Aplicação standalone do LP Express Studio, fora do WordPress.

- Front-end: React + Vite
- Domínio principal atual de staging: studio-app-lp.agenciacavalheri.com
- WordPress/WooCommerce: venda, pedido e token
- Studio: interface própria para montar/editar LPs
- Local Premium substituído por componente novo `lp-aurora-signature`, sem depender dos cards/visual antigo
- Edição visível e live de textos, imagens, cores, fontes e tamanhos no painel lateral
- `view=preview` abre a LP final em tela cheia, sem painel do Studio

Deploy atualizado a partir de `apps/lp-express-studio-standalone/frontend/dist`, com assets relativos para funcionar em domínio raiz ou subpasta HTTPS temporária.

Não salvar credenciais neste repositório.
