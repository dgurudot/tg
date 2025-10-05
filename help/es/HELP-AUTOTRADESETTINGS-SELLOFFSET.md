# **Compensación de Venta**

## Propósito:

- Esta configuración permite ajustar el precio de venta con una compensación fija.
- La compensación de venta se restará del precio de venta seleccionado (puede ser Ask, Bid o Mark. Predeterminado = Bid).

- La operación se realizará inicialmente al precio de venta recibido en la señal.
- Si no se ejecuta en 5 segundos, se reintentará la venta al precio de venta (puede ser Ask, Bid o Mark. Predeterminado = Bid) menos la compensación (predeterminado: 0.05).

## Ejemplo:

- Señal de venta de $200 con un precio de compra de $199 y un precio de venta de $201.
- Si la orden límite inicial de venta no se ejecuta a $200, se reintentará a $199 - 0.05 = $198.95.