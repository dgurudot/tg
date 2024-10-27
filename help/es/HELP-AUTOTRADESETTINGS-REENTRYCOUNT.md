# **Recuento de reintentos**

## Propósito: 

- Esta configuración le permite ajustar la cantidad de veces que reintentamos una orden limitada con compensación antes de colocar finalmente una orden de mercado.

## Ejemplo:

- Si su recuento de reintentos es 1, entonces la señal primero intentará completar la orden al precio recibido en la señal. 
- Si no se completa, entonces habrá solo 1 reintento (según la configuración del recuento de reintentos y se puede cambiar) y utilizará la demanda más la compensación para la señal de compra o la oferta menos la compensación para la señal de venta. 
- Una vez que se agoten los intentos de reintento, se colocará la orden de mercado.
