## PINTEREST
### Proyecto final sprint 6

Replicar una vista estándar de Pinterest exhibiendo un tablero con 40 imágenes.

**Requerimientos Técnicos**
Recorrer un archivo JSON para sacar la información requerida:

   - Título
   - Descripción
   - Nombre de usuario
   - Hashtag
   - Imagen

Desarrollar vista principal en versión desktop (tamaño grande y extra-grande).
Diagramción fluida, sin respetar columnas, simulando el comportamiento de despliegue de las imágenes de Pinterest.
Cargar 20 imágenes inicialmente. Al hacer scroll, se cargarán las 20 siguientes.
Al hacer click en la imagen, se debe desplegar un modal con el diseño entregado. La información se trae desde el JSON.

**El proyecto fue realizado con las siguientes dependencias NPM:**

    Dependencias de Desarrollo
       - Gulp ~v.3.9.1
       - Gulp-Concat ~v.2.6.1
       - Gulp-Minify-CSS ~v.1.2.4
       - Gulp-Sass ~v.3.0.0
       - Gulp-Uglify ~v.2.0.0

    Dependencias de Producción
       - jQuery ~v.3.1.1
       - Materialize ~v.0.97.8

**Levantamiento ambiente de desarrollo**

    Clonar repositorio.
    Posicionado en nuestro proyecto hacer correr npm install para descargar e instalar todas las dependencias utilizadas.
    Correr gulp para que se realizen las tareas especificadas.
    
