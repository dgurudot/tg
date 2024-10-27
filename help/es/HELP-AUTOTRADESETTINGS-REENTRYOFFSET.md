# **Compensación de reingreso**

## Propósito: 

- Esta configuración le permite ajustar la compensación del precio de compra (en el momento de la compra) o la oferta (en el momento de la venta). 
- La operación se realizará inicialmente al precio de compra recibido en la señal. 
- Si no se ejecuta dentro de los 5 segundos, se volverá a intentar comprar al precio de compra más la compensación (el valor predeterminado es 0,05). 
- De manera similar, si se recibe una señal de venta, la operación se realizará al precio de venta recibido en la señal, pero si no se ejecuta, se volverá a intentar comprar al precio de oferta menos la compensación (el valor predeterminado es 0,05). 

## Ejemplo:

- Señal de compra de $100 con oferta de $99 y oferta de $101. Si la orden límite inicial de compra no se completa a $100, se volverá a intentar comprar a $101 + 0,05 = $101,05. 

- Señal de venta de $200 con oferta de $199 y demanda de $201. Si la orden límite inicial de venta no se ejecuta en $200, se volverá a intentar en $199 - 0,05 = $198,95

