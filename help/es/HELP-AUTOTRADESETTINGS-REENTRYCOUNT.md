# **Recuento de Reintentos**

## Propósito:

- Esta configuración permite ajustar el número de reintentos para órdenes limitadas con compensación antes de colocar una orden a mercado.

## Ejemplo:

- Si el recuento de reintentos es 1, la señal intentará primero ejecutar la orden al precio recibido en la señal.
- Si no se ejecuta, solo habrá un reintento (según la configuración del recuento de reintentos, que puede modificarse) y se utilizará el precio de venta más la compensación para la señal de compra o el precio de oferta menos la compensación para la señal de venta.
- Una vez agotados los reintentos, se colocará la orden a mercado.