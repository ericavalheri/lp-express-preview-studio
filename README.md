# LP Express Studio Standalone

Aplicação standalone do LP Express Studio, fora do WordPress.

- Front-end: React + Vite
- Domínio principal atual de staging: studio-app-lp.agenciacavalheri.com
- WordPress/WooCommerce: venda, pedido e token
- Studio: interface própria para montar/editar LPs
- Edição visível e live de textos, imagens, cores, fontes e tamanhos no painel lateral
- Campos Negócio/Cidade/Segmento sincronizam a copy demo do modelo atual
- URLs demo por modo não misturam conteúdo: Local usa Clínica Aurora; Promo usa Moda Presente
- `view=preview` abre a LP final em tela cheia, sem painel do Studio
- Camada visual inspirada em templates tipo W3Layouts: topbar, grids de serviços, benefícios, prova, faixa de agendamento e campanha

Deploy atualizado a partir de `apps/lp-express-studio-standalone/frontend/dist`, com assets relativos para funcionar em domínio raiz ou subpasta HTTPS temporária.

Não salvar credenciais neste repositório.
