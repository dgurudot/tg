# **Deslocamento de ReEntrada**

## Objetivo: 

- Esta configuração permite que você ajuste o deslocamento do preço Ask (no momento da Compra) ou Bid (no momento da Venda). 
- A negociação será colocada inicialmente no preço de Compra recebido no sinal. 
- Se não for executada em 5 segundos, a nova tentativa comprará no Ask mais deslocamento (o padrão é 0,05). 
- Da mesma forma, se o sinal de venda for recebido, a negociação será colocada no preço de venda recebido no sinal, mas se isso não for executado, a nova tentativa será no Bid menos deslocamento (o padrão é 0,05).

## Exemplo:

- Sinal de compra $ 100 com Bid em $ 99 e Ask em $ 101. Se a ordem limite inicial para Compra não for preenchida em $ 100, a nova tentativa acontecerá em $ 101 + 0,05 = $ 101,05.

- Sinal de venda $200 com Bid em $199 e Ask em $201. Se a ordem limite inicial para Sell não for preenchida em $200, então a nova tentativa acontecerá em $199 - 0,05 = $198,95

