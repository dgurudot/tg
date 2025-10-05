# **Compensación de Reingreso**

## Propósito:

- Esta configuración permite ajustar la compensación entre el precio de compra (al momento de la compra) y el precio de oferta (al momento de la venta).
- La operación se realizará inicialmente al precio de compra recibido en la señal.
- Si no se ejecuta en 5 segundos, se reintentará la compra al precio de compra más la compensación (el valor predeterminado es 0,05).
- De igual forma, si se recibe una señal de venta, se realizará al precio de venta recibido en la señal; si no se ejecuta, se reintentará la compra al precio de oferta menos la compensación (el valor predeterminado es 0,05).

## Ejemplo:

- Señal de compra de $100 con una oferta de $99 y un precio de oferta de $101. Si la orden límite inicial de compra no se ejecuta a $100, se reintentará a $101 + 0,05 = $101,05.

Señal de venta de $200 con precio de oferta de $199 y precio de venta de $201. Si la orden límite inicial de venta no se ejecuta a $200, se realizará un nuevo intento a $199 - 0.05 = $198.95.