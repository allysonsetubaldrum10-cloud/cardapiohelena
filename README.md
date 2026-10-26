# Cardápio Digital de Salgados — projeto limpo

Site estático independente: **sem Supabase, sem npm, sem Vite, sem dependências externas**. Abra `index.html` no navegador ou publique como site estático.

## Funções
- Catálogo responsivo, carrinho, total, taxa de entrega, dados do cliente, horários e pedido pelo WhatsApp.
- Pix manual: copia a chave; o cliente envia o comprovante por WhatsApp. Não verifica pagamento automaticamente.
- Tela "Configurar" para nome, WhatsApp, Pix, horários, produtos, preços e URLs de fotos.
- Exportação/importação JSON para transportar configurações entre navegadores.

## Atenção antes de publicar
- **O painel não é protegido por senha.** As configurações são salvas apenas no `localStorage` do navegador e NÃO alteram o cardápio dos visitantes. Para uma loja real, substitua por configuração publicada no código ou backend com autenticação.
- O WhatsApp da loja deve ser preenchido antes de enviar pedidos.
- Não existe registro central de pedidos nem pagamento Pix integrado.
- O projeto é intencionalmente simples e deve ser testado na plataforma de hospedagem escolhida.
