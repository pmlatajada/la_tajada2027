# Peña Mixta La Tajada 2027

Aplicación web para gestionar fichas, grupos, asistencia y pagos. Este repositorio contiene solo la aplicación: no incluye fichas, claves ni conexión a la base de datos anterior.

## Primer uso

- Abre la aplicación desde una página HTTPS o desde un servidor local. GitHub Pages puede servir `index.html` desde la raíz de la rama `main`.
- Al entrar por primera vez, elige y repite tu contraseña. Se pedirá al desbloquear la edición, publicar o limpiar el historial en ese navegador. Es un bloqueo local de la interfaz, no una cuenta de usuario ni cifrado de las fichas.
- Para pasar tus datos, descarga **Exportar → JSON (backup)** en la aplicación anterior. Después, en la nueva, desbloquea la edición y pulsa **Importar**. No subas ese archivo a GitHub.
- Las fichas importadas quedan en el navegador donde las cargas; no se sincronizan entre dispositivos. Guarda copias JSON periódicamente en un lugar privado y evita importar fichas en dispositivos compartidos.

**Publicar en la web** solo permite enviar fichas a un repositorio privado con GitHub Pages de acceso restringido. **Borrar historial** oculta las entradas anteriores en el navegador, sin borrar el historial de GitHub.
