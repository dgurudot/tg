# **Contagem de ReEntradas**

## Objetivo: 

- Esta configuração permite que você ajuste o número de vezes que tentaríamos novamente a ordem limite com deslocamento antes de finalmente colocar a ordem de mercado.

## Exemplo:

- Se sua contagem de tentativas for 1, então o sinal tentará primeiro preencher a ordem no preço recebido no sinal. 
- Se não for preenchido, haverá apenas 1 nova tentativa (com base na configuração da contagem de tentativas e pode ser alterada) e usará o Ask mais deslocamento para o sinal Buy ou Bid menos deslocamento para o sinal Sell. 
- Uma vez que as tentativas de nova tentativa forem esgotadas, então a ordem de mercado será colocada.
