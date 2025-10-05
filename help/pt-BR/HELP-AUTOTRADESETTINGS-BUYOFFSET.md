# **Comprimento de Compra**

## Objetivo:

- Esta configuração permite ajustar o preço de compra por um deslocamento fixo. O deslocamento de compra será adicionado ao preço de compra selecionado (pode ser Venda, Compra ou Marca. Padrão = Venda).

- A negociação será colocada inicialmente ao preço de Compra recebido no sinal. Se não for executada em 5 segundos, a nova tentativa de compra será feita pelo preço de compra (pode ser Venda, Compra ou Marca. Padrão = Venda) mais o deslocamento (o padrão é 0,05).

## Exemplo:

- Sinal de compra de $100 com Oferta em $99 e Venda em $101. Se a ordem limite inicial de Compra não for executada em $100, a nova tentativa ocorrerá em $101 + 0,05 = $101,05.

## Exemplo:

- Sinal de compra de $100 com Oferta em $99 e Venda em $101. Se a ordem limite inicial de Compra não for executada em $100, a nova tentativa ocorrerá em $101 + 0,05 = $101,05.

