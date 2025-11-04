# \# 💍 Invitación Digital: Boda de Daniela \& Óscar

# 

# ¡Bienvenido/a al repositorio de nuestra invitación digital!

# 

# Este proyecto contiene los archivos esenciales para una página web sencilla que sirve como invitación de boda, incluyendo un contador de cuenta regresiva, una galería de fotos y un botón para agendar el evento en el calendario.

# 

# \## 📁 Archivos Incluidos

# 

# \* `index.html`: La estructura principal y el contenido de la invitación.

# \* `style.css`: Los estilos, la tipografía y el diseño adaptable (responsive).

# \* `README.md`: Este archivo de instrucciones.

# \* `fondo\_boda.jpg`: \*\*DEBES REEMPLAZAR\*\* esta imagen con la fotografía de fondo de la pareja.

# \* `foto\_1.jpg` a `foto\_10.jpg`: \*\*DEBES REEMPLAZAR\*\* estas imágenes con las fotos para la galería.

# 

# \## 🛠️ Personalización

# 

# Para usar esta invitación, sigue estos pasos:

# 

# 1\.  \*\*Reemplaza las Imágenes:\*\*

# &nbsp;   \* Sube tu foto principal y renómbrala a `fondo\_boda.jpg`.

# &nbsp;   \* Sube tus 10 fotos para la galería y nómbralas de `foto\_1.jpg` a `foto\_10.jpg`.

# 

# 2\.  \*\*Ajusta la Fecha del Contador (`index.html`):\*\*

# &nbsp;   \* En la sección `<script>`, localiza la línea:

# &nbsp;       ```javascript

# &nbsp;       const weddingDate = new Date("Dec 26, 2025 17:00:00").getTime();

# &nbsp;       ```

# &nbsp;   \* Asegúrate de que la fecha y hora (`"Dec 26, 2025 17:00:00"`) coincidan con tu evento. El formato es "Mes Día, Año Hora:Minuto:Segundo".

# 

# 3\.  \*\*Configura el Enlace de Google Maps (`index.html`):\*\*

# &nbsp;   \* El `<iframe>` actualmente muestra un mapa genérico. \*\*DEBES GENERAR\*\* el código \*embed\* correcto de Google Maps para la ubicación final (Ejido La Libertad, Torreón, Coahuila) y reemplazar el `<iframe>` proporcionado en el archivo.

# 

# 4\.  \*\*Despliegue (Hosting):\*\*

# &nbsp;   \* Sube estos tres archivos (`index.html`, `style.css`, `README.md`) y tus 11 imágenes a un servicio de hosting web (como GitHub Pages, Netlify o cualquier otro).

# 

# ---

# 

# \## 📅 Función "Agregar al Calendario"

# 

# El botón funciona generando un enlace para \*\*Google Calendar\*\* con la información de tu evento:

# 

# \* \*\*Título:\*\* Boda de Daniela Sandoval y Óscar Gaytán

# \* \*\*Fechas:\*\* 26 de diciembre de 2025 de 17:00 a 20:00 (ajustado con una duración de 3 horas por defecto).

# \* \*\*Ubicación:\*\* Ejido La Libertad, Torreón, Coahuila, México.

# 

# ---

