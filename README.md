# SEU BURGUER
Sistema de cardápio online de uma Hambrugueria fictícia onde o cliente escolhe os produtos no projeto e após finalizar é encaminhado uma mensagem com todos os itens escolhidos no WhatsApp da empresa.

# Futuras integrações 
### Integração com a WhatsApp API
- Utilizar a [API do WhatsApp Business](https://www.twilio.com/whatsapp) para permitir a comunicação automática entre o bot e o cliente.
- A integração pode ser feita através de plataformas como [Twilio](https://www.twilio.com/whatsapp), [Zenvia](https://www.zenvia.com/), ou [Botpress](https://botpress.com/).
  
### Desenvolvimento do Bot
- Criar um bot que envie mensagens automáticas para os clientes após finalizarem a escolha dos itens no cardápio.
- O fluxo do bot pode ser programado de acordo com a sequência de ações:
  - Solicitar endereço de entrega.
  - Confirmar itens escolhidos.
  - Informar o valor total.
  - Solicitar o pagamento.

### Coleta de Dados
- O bot deve coletar:
  - **Endereço de entrega**: “Por favor, informe seu endereço de entrega.”
  - **Confirmação de itens**: “Você escolheu os seguintes itens... Confirma?”
  - **Forma de pagamento**: Opções como "transferência bancária", "cartão de crédito", ou "link de pagamento".

### Integração com Sistema de Pagamento
- Conectar o bot com um sistema de pagamento, como [PayPal](https://www.paypal.com), [MercadoPago](https://www.mercadopago.com.br), ou [PagSeguro](https://www.pagseguro.uol.com.br/).
- O bot gera um **link de pagamento** que o cliente pode clicar para concluir a transação.

### Envio de Resumo
- Após o pagamento ser confirmado, o bot envia um resumo para o cliente e para o WhatsApp da loja, com:
  - Itens adquiridos.
  - Valor total.
  - Endereço de entrega.
  - Status do pagamento.

### Acompanhamento e Suporte
- O bot pode enviar mensagens de acompanhamento, como:
  - “Seu pedido está em preparo.”
  - “Seu pedido foi enviado e está a caminho.”
- Oferecer suporte adicional, caso o cliente tenha alguma dúvida ou problema com o pedido.

## Benefícios:
- Automatização do processo de vendas.
- Facilidade para o cliente concluir a compra diretamente no WhatsApp.
- Aumento na eficiência operacional da loja.
