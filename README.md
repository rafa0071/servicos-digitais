# Estúdio Digital — site de venda de serviços

Site de demonstração para vender serviços digitais com pacotes de preço fechado e checkout online.

**Demo:** https://rafa0071.github.io/servicos-digitais/

## Páginas

- **Início**: proposta de valor, passos do processo, pacotes mais pedidos e perguntas frequentes
- **Serviços**: todos os pacotes e a descrição dos serviços
- **Checkout**: escolha do pacote, dados do cliente e pagamento por cartão (Stripe) ou PayPal

## Editar preços e textos

Tudo está no array `PACKAGES` no topo do script em `index.html`: nome, preço, prazo, revisões, itens incluídos e os links de pagamento.

Para ativar pagamentos reais, crie um **Payment Link** no Stripe e/ou um botão de pagamento no PayPal para cada pacote e cole o URL em `stripe` e `paypal`. Os dados do cartão são tratados apenas pelo Stripe ou PayPal.

## Executar

Abra `index.html` no navegador. Não precisa de instalação nem de servidor.

## Licença

MIT
