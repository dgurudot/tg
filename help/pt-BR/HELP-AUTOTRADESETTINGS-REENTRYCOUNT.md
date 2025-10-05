# **Contagem de Reentradas**

## Objetivo:

- Esta configuração permite ajustar o número de vezes que tentaríamos executar uma ordem limitada com offset antes de finalmente abrir uma ordem a mercado.

## Exemplo:

- Se a sua contagem de tentativas for 1, o sinal tentará primeiro executar a ordem ao preço recebido no sinal.
- Se não for executada, haverá apenas 1 nova tentativa (com base na configuração da contagem de tentativas e pode ser alterada) e usará o valor de Venda mais offset para Compra ou o Valor de Compra menos offset para Venda.
- Assim que as tentativas de tentativa forem esgotadas, a ordem a mercado será aberta.

