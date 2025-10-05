# **Compensação de Venda**

## Objetivo:

- Esta configuração permite ajustar o preço de venda por compensação fixa.
- A compensação de venda será subtraída do preço de venda selecionado (pode ser Venda, Compra ou Marca. Padrão = Compra).

- A negociação será colocada inicialmente ao preço de venda recebido no sinal.
- Se não for executada em 5 segundos, a nova tentativa de venda será feita ao preço de venda (pode ser Venda, Compra ou Marca. Padrão = Compra) menos a compensação (o padrão é 0,05).

## Exemplo:

- Sinal de venda de $200 com Compra em $199 e Venda em $201.
- Se a ordem limite inicial de Venda não for executada em $200, a nova tentativa será feita em $199 - 0,05 = $198,95

