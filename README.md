# Fundamentos Web: HTML5 y CSS3

**INFORMACIÓN DE CONTACTO DEL CREADOR**

    Daniel Bueno Pacheco
    linkedin.com/in/daniel-bueno-pacheco/

## Creación de un sitio web para plataforma online de contenido digital.

### Consideraciones generales

- No se permite el uso de librerías y frameworks externos como Bootstrap, Spectre.css o similares.
- Se deberá crear una o más hojas de estilo CSS para aplicar el diseño deseado a la web.
- La página web debe visualizarse correctamente en las versiones actuales de Google Chrome, Mozilla Firefox y Microsoft Edge.
- No se requiere el uso de interacción mediante JavaScript.

### Contenido de la práctica

El objetivo es construir la estructura web de una plataforma de streaming de contenido digital al estilo de Netflix o HBO para distribuir series y películas a cualquier dispositivo conectado a internet que disponga de un navegador web moderno. Nuestro público es de diferentes edades y condiciones y queremos que dispongan de la mejor experiencia de usuario independientemente del tamaño de su pantalla.

Como estamos buscando un producto mínimo viable que podamos poner en marcha enseguida nos centraremos solamente en tres pantallas o secciones:

1. Al llegar a la plataforma se debe mostrar un formulario de login para acceder al contenido. En este formulario se debe implementar:

   a. Un campo para el email, que servirá como nombre de usuario

   b. Un campo para la contraseña

   c. Un botón para realizar el login y acceder al contenido

   d. Un enlace para iniciar el proceso de recordar una contraseña olvidada. Redirecciona a una pagina con un mensaje básico.

2. La pantalla principal del contenido que contendrá, al menos, los siguientes elementos:

   a. Un menú superior, que debe incluir el logotipo de la plataforma, opciones para acceder a la sección de novedades, series, películas o favoritos, un formulario de búsqueda y la opción para cerrar la sesión.

   b. Una “rejilla” de películas o series de forma que en cada elemento se muestre una miniatura de la serie/película/episodio. Además, al situar el ratón encima, se mostrará sobre la miniatura información adicional: título, calificación, año de publicación y sinopsis resumida.

   c. Cada película o serie contendrá un icono que permitirá marcarla como favorita. Si el contenido está marcado como favorito, el icono se mostrará de forma diferente de manera que se distinga fácilmente el contenido favorito del resto.

3. Una ficha detalle de la película/serie/episodio. Debe contener al menos:

   a. El mismo menú superior de la pantalla principal

   b. Información básica de la película/serie/episodio: título, calificación, año de publicación, sinopsis completa y listado de actores.

   c. Carátula o trailer. El trailer debe poder reproducirse en la propia página. En caso de tratarse de un vídeo no se acepta la inclusión mediante marcos iframe.

   d. “Rejilla” con contenido relacionado, que se usará para los episodios en el caso de una serie o para películas similares en el caso de las películas.

4. Crear una página de error 404 Not Found. La página debe contener de forma destacada el código y el título del error (404, Página no encontrada). Para evitar que el visitante abandone la página, incluirá (al menos) una de estas dos opciones: un enlace para volver al inicio, un mapa del contenido del sitio web.

## Detalles de prueba

### Tras bajarse el repositorio remoto a tu local, se usará Visual Code para probarlo. Con BrowserSync se levantará un servidor para probarlo rapidamente. Contenido:

1. Primera pagina es el login. Introduce un usuario(e-mail) y contraseña y te redireccionará a la página de series(actualmente no hay películas)

2. Página de series. Puedes pasar el ratón sobre una serie y te mostrará una descripción. Si pulsas el icono del corazón, pondrás como favorito la serie. Si pinchas en la imagen te redireccionará al contenido de la serie.

3. La página de cada serie es la misma. Dispone de un título, trailer, descripción completa y una rejilla a la derecha de la lista de episodios. Si pinchas en un episodio, verás una descripción del mismo.

4. Página 404.html. Para acceder introduce la página directamente desde la URL. Verás un mensaje descriptivo y un enlace para volver a la primera página.
