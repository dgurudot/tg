# **Deslocamento de venda**

## Objetivo: 

- Esta configuração permite que você ajuste o preço de venda por deslocamento fixo. 
- O deslocamento de venda será subtraído do preço de venda selecionado (pode ser Ask, Bid ou Mark. Padrão = Bid).

- A negociação será colocada inicialmente no preço de venda recebido no sinal. 
- Se não for executada em 5 segundos, a nova tentativa venderá no preço de venda (pode ser Ask, Bid ou Mark. Padrão = Bid) menos o deslocamento (o padrão é 0,05). 

## Exemplo:

- Sinal de venda $ 200 com Bid em $ 199 e Ask em $ 201. 
- Se a ordem limite inicial para venda não for preenchida em $ 200, a nova tentativa acontecerá em $ 199 - 0,05 = $ 198,95
