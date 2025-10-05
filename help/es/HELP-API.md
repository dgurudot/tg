# 🔑 Administración de API

La pantalla **Administración de API** le permite administrar sus claves de API de TradeGrub, las cuales se utilizan para integraciones seguras con servicios externos como **TradingView** o **API REST personalizadas**.

---

## 📋 Tabla de claves de API

Todas las claves de API existentes se muestran en una tabla sencilla y fácil de leer.

### Columnas de la tabla
- **Nombre** → La etiqueta que asigna al crear la clave.
- **Clave** → El identificador único utilizado para la autenticación.
- **Permisos** → Define el acceso a la clave (p. ej., `TradingView`, `REST`).
- **Fecha de creación** → La fecha en que se generó la clave.
- **Acciones** → Use el icono 🗑️ **Eliminar** para eliminar la clave de API de forma permanente.

> ⚠️ **Importante:** Eliminar una clave API revoca inmediatamente su acceso.
> Cualquier servicio conectado (como los webhooks de TradingView) que use esa clave dejará de funcionar.

---

## ➕ Crear una nueva clave API

Pulse el botón **“+” (Añadir)** en la esquina superior derecha para crear una nueva clave.

Se le pedirá que especifique:

| Campo | Descripción |
|--------|--------------|
| **Nombre** | Un nombre descriptivo para identificar esta clave (p. ej., *Señales de TradingView*). |
| **Permisos** | Elija uno o ambos: - **TradingView** → Necesario para recibir y procesar señales de webhooks de TradingView. - **REST** → Necesario para acceder a las API REST de TradeGrub. |

Una vez creada, la nueva clave API aparecerá instantáneamente en la vista de tabla.

> 💡 Puedes crear varias claves; por ejemplo, una para tu cuenta personal de TradingView y otra para tu integración REST automatizada.

---

## 🔐 Visibilidad del Secreto de API

Al crear una nueva clave API, se genera un **secreto** que se muestra **solo una vez** por razones de seguridad.

Tendrás la opción de **copiarlo** durante la creación; asegúrate de guardarlo de forma segura.


> ⚠️ **Nota:**
> El secreto **no se puede volver a ver posteriormente**.
> Debes guardarlo de forma segura, ya que será necesario al usar la clave API en integraciones de **TradingView** o **API REST**.

---

## ⚙️ Mejores prácticas

- Mantén tus claves API **privadas y seguras**.
- Usa **claves separadas** para diferentes integraciones.
- Revoca (elimina) las claves no utilizadas o comprometidas inmediatamente.
- Nunca compartas tu clave API públicamente ni en capturas de pantalla.

---

## 🧩 Ejemplos de uso

| Escenario | Permiso requerido |
|-----------|---------------------|
| Envío de señales de compra/venta de TradingView | TradingView |
| Llamadas a la API REST a TradeGrub | REST |
| Configuración de automatización de trading combinada | TradingView + REST |

---

## 🆘 Consejos
- Toca el icono de **información (ℹ️)** en la esquina superior derecha para obtener ayuda rápida.
- Siempre puedes volver a crear una clave si se borra accidentalmente.
- Las acciones de la clave API se sincronizan instantáneamente con tu cuenta; no es necesario reiniciar la aplicación.