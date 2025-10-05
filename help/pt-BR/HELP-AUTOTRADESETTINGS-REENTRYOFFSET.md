# **Deslocamento de Reentrada**

## Objetivo:

- Esta configuração permite ajustar o deslocamento do preço de venda (no momento da compra) ou do preço de venda (no momento da venda).
- A operação será colocada inicialmente ao preço de compra recebido no sinal.
- Se não for executada em 5 segundos, a nova tentativa de compra será feita pelo preço de venda mais o deslocamento (o padrão é 0,05).
- Da mesma forma, se o sinal de venda for recebido, a operação será colocada pelo preço de venda recebido no sinal, mas se este não for executado, a nova tentativa será feita pelo preço de venda menos o deslocamento (o padrão é 0,05).

## Exemplo:

- Sinal de compra de $100 com o preço de compra a $99 e o preço de venda a $101. Se a ordem limite inicial de compra não for executada a $100, a nova tentativa será feita a $101 + 0,05 = $101,05.

- Sinal de venda de US$ 200 com Bid de US$ 199 e Ask de US$ 201. Se a ordem limite inicial de Venda não for executada em US$ 200, uma nova tentativa será feita em US$ 199 - 0,05 = US$ 198,95.

