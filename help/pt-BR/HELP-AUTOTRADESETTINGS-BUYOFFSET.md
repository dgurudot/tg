# **Comprar Offset**

## Objetivo: 

- Esta configuração permite que você ajuste o preço de compra por offset fixo. O offset de compra será adicionado ao preço de compra selecionado (pode ser Ask, Bid ou Mark. Padrão = Ask).

- A negociação será colocada inicialmente no preço de compra recebido no sinal. Se não for executada em 5 segundos, a nova tentativa comprará no preço de compra (pode ser Ask, Bid ou Mark. Padrão = Ask) mais offset (o padrão é 0,05). 

## Exemplo:

- Sinal de compra $ 100 com Bid em $ 99 e Ask em $ 101. Se a ordem limite inicial para compra não for preenchida em $ 100, a nova tentativa acontecerá em $ 101 + 0,05 = $ 101,05.
