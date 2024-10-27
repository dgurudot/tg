# **Compensación de venta**

## Propósito: 

- Esta configuración le permite ajustar el precio de venta con una compensación fija. 
- La compensación de venta se restará del precio de venta seleccionado (puede ser Ask, Bid o Mark. Predeterminado = Bid).

- La operación se colocará inicialmente al precio de venta recibido en la señal. 
- Si no se ejecuta dentro de los 5 segundos, entonces se volverá a intentar vender al precio de venta (puede ser Ask, Bid o Mark. Predeterminado = Bid) menos la compensación (el valor predeterminado es 0.05). 

## Ejemplo:

- Señal de venta $200 con Bid a $199 y Ask a $201. 
- Si la orden límite inicial para vender no se completa a $200, entonces se volverá a intentar a $199 - 0.05 = $198.95
