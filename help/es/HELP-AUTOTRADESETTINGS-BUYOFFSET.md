# **Compensación de Compra**

## Propósito:

- Esta configuración permite ajustar el precio de compra con una compensación fija. La compensación de compra se añadirá al precio de compra seleccionado (puede ser Ask, Bid o Mark. Predeterminado = Ask).

- La operación se realizará inicialmente al precio de compra recibido en la señal. Si no se ejecuta en 5 segundos, se reintentará la compra al precio de compra (puede ser Ask, Bid o Mark. Predeterminado = Ask) más la compensación (predeterminado: 0.05).

## Ejemplo:

- Señal de compra de $100 con un precio de compra de $99 y un precio de compra de $101. Si la orden límite inicial de compra no se ejecuta a $100, se reintentará a $101 + 0.05 = $101.05.

