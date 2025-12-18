# Proyecto-Web-Ejemplo

Proyecto creado para curso



Para clonar el proyecto, copia la URL del repositorio en GitHub y ejecuta en tu terminal: git clone <URL>. Esto descargará el código a tu equipo. Luego entra a la carpeta del proyecto con cd Proyecto-Web-Ejemplo (o el nombre que tenga tu repo). Como es un proyecto simple de HTML y CSS, puedes ejecutarlo de forma directa abriendo el archivo index.html con tu navegador (doble clic o “Abrir con…”). Así verás la página renderizada usando los estilos definidos en styles.css.



Si prefieres simular un entorno local más parecido a un despliegue web (y evitar problemas de rutas o caché), levanta un servidor local. Por ejemplo, si tienes Python instalado, ejecuta python -m http.server 5500 dentro de la carpeta del proyecto. Luego abre tu navegador y visita http://localhost:5500. También puedes usar extensiones como “Live Server” en Visual Studio Code: abres la carpeta del proyecto, haces clic derecho sobre index.html y seleccionas “Open with Live Server”. Con eso obtendrás recarga automática al guardar cambios y podrás probar el sitio rápidamente en tu PC.

## Ramas del proyecto



Este repositorio utiliza ramas para separar el trabajo base de las mejoras visuales y facilitar la integración de cambios.



\### `main`

\- Contiene la versión estable del proyecto.

\- Incluye la estructura base del sitio (HTML) y los estilos principales (CSS).

\- Aquí se integran los cambios finales aprobados (por ejemplo, mediante Pull Request).



\### `feature-mejora-estilo`

\- Rama destinada a mejorar el diseño y la presentación visual.

\- Implementa ajustes de estilos

\- Se usa para realizar commits frecuentes de cambios visuales y luego integrar a `main` mediante un Pull Request.

