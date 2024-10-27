# **Compensación de compra**

## Propósito: 

- Esta configuración le permite ajustar el precio de compra mediante una compensación fija. La compensación de compra se agregará al precio de compra seleccionado (puede ser Ask, Bid o Mark. Predeterminado = Ask).

- La operación se colocará inicialmente al precio de compra recibido en la señal. Si no se ejecuta dentro de los 5 segundos, entonces se volverá a intentar comprar al precio de compra (puede ser Ask, Bid o Mark. Predeterminado = Ask) más la compensación (el valor predeterminado es 0.05). 

## Ejemplo:

- Señal de compra de $100 con Bid a $99 y Ask a $101. Si la orden límite inicial de compra no se completa a $100, entonces se volverá a intentar a $101 + 0.05 = $101.05.
