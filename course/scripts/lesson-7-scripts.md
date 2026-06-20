# Lesson 7 - Script

Hola, bienvenidos a la lección número 7.

En la clase pasada construimos la estructura HTML de nuestra tarjeta de presentación. Ya tenemos una imagen, un nombre, una descripción, una lista de intereses y un enlace.

Ahora vamos a usar CSS para mejorar la apariencia de esta misma tarjeta. Queremos que se vea más ordenada y más atractiva visualmente.

Primero observamos cómo se encuentra la página en este momento. El contenido ya está completo, pero todavía se ve muy simple. Esto es normal porque HTML solo se encarga de la estructura. CSS nos ayudará a cambiar colores, tamaños, espacios y alineación. En otras palabras, CSS nos ayuda a dar estilo a nuestra página web.

Antes de comenzar, hay que recordar algo importante: no basta con escribir CSS sin más. Para que un estilo se aplique correctamente, el elemento en HTML debe tener el selector adecuado. Por ejemplo, si queremos dar estilo a la imagen con la clase `profile-image`, entonces la etiqueta `img` debe tener esa clase en el HTML.

Ahora sí, empecemos con el estilo general de la página. Vamos a trabajar primero con el selector `body`. Aquí podemos cambiar la fuente del texto usando `font-family`. Por ejemplo, podemos usar Arial para que toda la página tenga una fuente más limpia y fácil de leer.

También podemos agregar `padding` para que el contenido no esté pegado a los bordes de la pantalla. Esto ayuda a que la página se vea más cómoda y ordenada.

Después trabajaremos con la clase `card`, que es el contenedor principal de nuestra tarjeta. Aquí podemos cambiar varias cosas importantes: el color de fondo, el ancho máximo, el margen automático para centrarla, el espacio interno con `padding` y los bordes redondeados con `border-radius`.

Al aplicar `border-radius`, la tarjeta deja de verse como un rectángulo rígido y se ve un poco más moderna. Si además queremos agregar una sombra, podemos usar `box-shadow`. Esto ayuda a que la tarjeta resalte un poco más sobre el fondo.

También podemos centrar el contenido con `text-align: center;`. Así, el texto y los elementos de la tarjeta se verán más ordenados.

Ahora vamos a mejorar la lista de intereses. Por defecto, la lista muestra viñetas o puntos, pero en este diseño no queremos que aparezcan. Para quitarlos, seleccionamos `ul` y usamos `list-style: none;`.

Después podemos dar estilo a cada elemento de la lista con `li`. Por ejemplo, podemos agregar un color de fondo, un margen para separarlos, un `padding` para que tengan espacio interno y un `border-radius` para redondear sus esquinas. De esta forma, cada interés se verá como un pequeño bloque dentro de la tarjeta.

Finalmente, vamos a cambiar la apariencia del enlace. Como el enlace tiene la clase `profile-link`, podemos seleccionar esa clase y aplicarle estilos específicos. Podemos darle un color de fondo, cambiar el color del texto, quitar el subrayado, agregar espacio interno y redondear los bordes.

Además, usamos `display: inline-block;` para que el enlace se comporte más como un botón. Así conseguimos una apariencia mucho más limpia y agradable.

Como puedes ver, con CSS podemos mejorar bastante la presentación de una estructura HTML sencilla. Podemos cambiar colores, tamaños, espacios, alineación y muchos otros detalles visuales.

Antes de terminar, recuerda estos consejos: usa clases para aplicar estilos a elementos específicos, no exageres con los colores, deja suficiente espacio entre los elementos y limita el ancho del contenedor para que el contenido sea fácil de leer.

Con esto ya tenemos una tarjeta de presentación sencilla, clara y agradable visualmente.

Gracias por acompañarme en esta lección.
