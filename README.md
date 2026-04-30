# Sweet Bakery

Repositorio de la aplicación Sweet Bakery.

## Descripción

Este proyecto contiene una tienda/bakery con frontend estático y backend en Node.js/Express.

- `backend/` contiene el servidor, API y modelos de datos.
- `frontend/` contiene las páginas HTML, CSS y JavaScript del sitio.

## Enlace de producción

- Producción: https://sweet-bakery-psi.vercel.app/

> Este enlace puede corresponder a una versión desplegada del frontend. Lo incluyo aquí para que esté disponible como referencia.

## Estructura del proyecto

- `backend/package.json`: dependencias y scripts del servidor.
- `backend/server.js`: punto de entrada del backend.
- `backend/controllers/`: controladores de la API.
- `backend/models/`: esquemas de datos.
- `backend/routes/`: rutas del servidor.
- `backend/services/`: servicios adicionales (por ejemplo, WhatsApp).
- `frontend/`: contenido web estático.

## Cómo ejecutar localmente

### Backend

1. Ir a la carpeta `backend/`.
2. Instalar dependencias:
   ```bash
   npm install
   ```
3. Iniciar el servidor:
   ```bash
   npm run dev
   ```
4. El servidor escuchará en `localhost:3000` (según configuración de `server.js`).

### Frontend

El frontend está en archivos estáticos dentro de `frontend/`.

Para probar localmente, puede abrir los archivos HTML directamente en el navegador o usar un servidor simple si prefiere.

## Notas

- Si el enlace de producción está disponible, se refiere al despliegue actual del sitio.
- Ajustar la configuración de backend y variables de entorno según sea necesario.
- El proyecto actualmente no tiene un README previo; este archivo sirve como guía inicial.
