# DIW-06
Tarea 6 Diseño de Interfaces Web

Crea los scripts JQuery necesarios para visualizar la página web como se describe a continuación:<br>
    1. Inicialmente la página debe mostrar los compositores y el primer párrafo de la descripción de cada uno de ellos.<br>
    2. Al seleccionar algún botón del menú (Compositores o Intérpretes) la imagen que se muestra en el div con id=”panorama” cambiarán secuencialmente desde la 1 hasta la 15 indefinidamente, es decir, cuando llega a la 15 comenzará el ciclo de nuevo.
- Solamente la imagen debe cambiar cuando se pulse un botón diferente al que se ha pulsado con anterioridad, es decir, si se pulsa sobre el mismo botón repetidas veces la imagen no cambia. Como puedes comprobar en los archivos del proyecto, dentro de la carpeta ./img/panorama encontrarás 15 imágenes que van desde la img1.jpghasta la img15.jpg.
- Al seleccionar la opción de menú Compositores deben mostrarse los artículos pertenecientes a los compositores y al seleccionar la opción de menú Intérpretesdeben mostrarse los artículos pertenecientes a los intérpretes.
- Utiliza un efecto fadeIn con un tiempo de 600ms para hacer aparecer los artículos correspondientes.
- Utiliza un efecto fadeOut con un tiempo de 200ms para ocultar aquellos artículos que no deben visualizarse.
- La imagen debe cambiarse dinámicamente desde el script JQuery manteniendo las propiedades css originales.<br>
    3. Cada artículo, sea de compositores o intérpretes, inicialmente, tiene un texto (Seguir leyendo...) que permite mostrar el texto completo y una vez que se visualiza todo el texto aparece una opción (Mostrar menos…) que oculta el texto mostrado.<br>
- Para mostrar los textos utiliza un efecto fadeIn con un tiempo de 1000ms.
- Para ocultar los textos utiliza un efecto slideUp con un tiempo de 1000ms.
- No olvides mostrar nuevamente el texto Seguir leyendo… una vez que hayas ocultado el texto. Utiliza algún efecto para mostrarlo.<br>
    4. Cada artículo correspondiente a los intérpretes tiene un botón que al seleccionarlo permite visualizar u ocultar un video.<br>
- Utiliza los efectos slideUp y slideDown con un tiempo de 1000ms para realizar lo pedido.

IMPORTANTE
- Escribe los scripts entre las etiquetas <script> del archivo html.
- No debes modificar el código html
- No debes modificar el código CSS
- Analiza el código html y familiarízate con las clases y los id’s de cada elemento.
- Mira el video adjunto para entender las funcionalidades que se solicitan.
- En el apartado 2. Información de Interés encontrarás el esqueleto del ejercicio que contiene todos los archivos necesarios para la realización de la tarea.
