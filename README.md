# CENIIT Conecta

Prototipo de aplicación web y móvil (PWA) para el **Centro de Investigación e Innovación Tecnológica (CENIIT)** de la Universidad Nacional de La Rioja.

Reúne en un solo lugar los proyectos del Centro, un calendario de charlas, capacitaciones y presentaciones, y la ubicación del CENIIT. Incluye un panel de administración para cargar eventos y proyectos.

Proyecto de la materia *Tecnologías multimediales para desarrollo educativo* · Licenciatura en Diseño y Producción Multimedia · UNLaR.

## Funcionalidades

- Inicio con presentación del CENIIT, próximos eventos, proyectos destacados y ubicación.
- Proyectos con buscador por nombre y filtros por temática y año.
- Calendario con filtros por tipo, temática, fecha, sede y horario; eventos agrupados en Hoy, Próximos y Finalizados.
- Ficha de evento con horario, duración, lugar, mapa, modalidad e inscripción.
- Botón "Agendar" y recordatorio en Google Calendar.
- Modo claro y modo oscuro.
- Panel de administración con login para cargar, editar y eliminar eventos y proyectos.
- Se puede instalar en el celular con el logo del CENIIT como ícono.

## Cómo publicarla con GitHub Pages

1. Subí todos los archivos de esta carpeta a un repositorio (por ejemplo `ceniit-conecta`).
2. En el repositorio, entrá a **Settings → Pages**.
3. En **Source**, elegí **Deploy from a branch**, rama `main` y carpeta `/ (root)`. Guardá.
4. En uno o dos minutos la app queda publicada en `https://TU-USUARIO.github.io/ceniit-conecta/`.

## Instalarla en el celular

- **Android (Chrome):** abrí el link, tocá ⋮ y elegí **Agregar a la pantalla principal** o **Instalar app**.
- **iPhone (Safari):** abrí el link, tocá el botón Compartir y elegí **Agregar a inicio**.

## Nota sobre los datos

Es un prototipo sin servidor: los eventos y proyectos que se cargan desde el panel de administración se guardan en el dispositivo donde se cargaron. Para que se compartan entre todos los visitantes haría falta una base de datos (por ejemplo, Firebase o Supabase).

## Estructura

```
index.html              App completa (HTML, CSS y JavaScript)
manifest.webmanifest    Datos de instalación (nombre, colores, íconos)
sw.js                   Funcionamiento sin conexión
icons/                  Íconos con el logo del CENIIT
```
