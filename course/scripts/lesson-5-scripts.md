# Lesson 5 - Scripts
Hola, bienvenidos a la clase 5 del curso de **HTML y CSS** de nuestra startup **Aurora**.

En esta clase vamos a crear una página sencilla usando HTML y CSS. La idea es ver cómo CSS nos permite cambiar el color, el fondo, la fuente, el tamaño del texto, los bordes y la posición de los elementos dentro de una página web.

Para este ejemplo vamos a trabajar en **CodeSandbox**. También existen otras herramientas como **JSFiddle** o editores similares, pero en este caso usaremos CodeSandbox porque se parece más a trabajar en un entorno de desarrollo como Visual Studio Code.

Primero, creamos un nuevo proyecto. Seleccionamos la opción de **HTML + CSS** y le colocamos un nombre, por ejemplo: **Prueba CSS**. Luego creamos el proyecto.

Al abrirlo, CodeSandbox ya nos genera una plantilla básica. Aquí podemos ver la estructura principal de HTML, pero lo más importante para esta clase es esta línea:

```html
<link rel="stylesheet" href="styles.css">
```

Esta línea conecta nuestro archivo HTML con el archivo CSS. En este caso, el archivo CSS se llama **styles.css**. Gracias a esta conexión, todos los estilos que escribamos en CSS se aplicarán a nuestra página HTML.

Por ejemplo, en el archivo CSS podemos ver una regla para la etiqueta `h1`:

```css
h1 {
  text-decoration: underline;
}
```

Esto significa que todos los títulos `h1` tendrán un subrayado. Si borramos esta regla y guardamos con **Ctrl + S**, el subrayado desaparece.

Ahora vamos a crear algunos elementos en HTML.

Como ya hemos visto antes, HTML funciona con etiquetas. Por ejemplo, podemos escribir un `div`:

```html
<div>Hola, CSS</div>
```

También podemos agregar un título:

```html
<h1>Bienvenidos</h1>
```

Y un campo de texto usando `input`:

```html
<input type="text" placeholder="Ingresar texto">
```

El atributo `placeholder` sirve para mostrar un texto de ayuda dentro del campo.

Ahora vamos a modificar estos elementos usando CSS.

Primero, recordemos que podemos seleccionar una etiqueta completa. Por ejemplo, si escribimos:

```css
h1 {
  text-decoration: underline;
}
```

Todos los elementos `h1` tendrán subrayado.

También podemos aplicar estilos a todos los `div`. Por ejemplo:

```css
div {
  color: violet;
  font-size: 50px;
}
```

Con esto, todos los textos dentro de etiquetas `div` cambiarán a color violeta y tendrán un tamaño de fuente de 50 píxeles.

Pero aquí aparece un problema: ¿qué pasa si tenemos varios `div` y no queremos que todos tengan el mismo estilo?

Por ejemplo:

```html
<div>Hola, CSS</div>
<div>Hola mundo</div>
```

Si usamos `div` en CSS, ambos elementos tendrán el mismo color y el mismo tamaño. Para diferenciar uno de otro, podemos usar una **clase**.

Una clase se agrega con el atributo `class`:

```html
<div class="mundo">Hola mundo</div>
```

Luego, en CSS, para seleccionar una clase usamos un punto antes del nombre:

```css
.mundo {
  font-size: 80px;
}
```

De esta manera, solo el elemento que tenga la clase `mundo` recibirá ese estilo.

También podemos hacer lo mismo con el campo de texto. Por ejemplo:

```html
<input class="entrada" type="text" placeholder="Ingresar texto">
```

Y en CSS:

```css
.entrada {
  border-radius: 20px;
  font-size: 20px;
}
```

La propiedad `border-radius` sirve para redondear los bordes del elemento. En este caso, el input tendrá bordes más redondeados y un texto más grande.

Ahora vamos a cambiar la fuente del texto.

Podemos usar la propiedad `font-family`. Por ejemplo:

```css
body {
  font-family: Arial, sans-serif;
}
```

Al aplicar esto al `body`, toda la página usará esa fuente. El `body` representa el cuerpo completo del documento HTML, por eso cualquier estilo que pongamos ahí se aplicará de forma general.

También podemos cambiar el color de fondo de toda la página:

```css
body {
  font-family: Arial, sans-serif;
  background-color: aquamarine;
}
```

Con `background-color` cambiamos el fondo. En este caso, el fondo será de color aquamarine.

Ahora vamos a trabajar con la posición de los elementos.

Por defecto, los elementos aparecen alineados hacia la izquierda. Pero con CSS podemos cambiar su alineación. Por ejemplo, podemos agrupar algunos elementos dentro de un `div`:

```html
<div class="texto">
  <h1>Bienvenidos</h1>
  <div>Hola, CSS</div>
</div>
```

Luego, en CSS, escribimos:

```css
.texto {
  text-align: center;
}
```

Con `text-align: center`, todo el contenido dentro del `div` con clase `texto` se alineará al centro.

También podemos agregar un color de fondo a esa sección para diferenciarla mejor:

```css
.texto {
  text-align: center;
  background-color: blue;
}
```

Ahora esa sección tendrá un fondo azul.

Si queremos separar esta sección de los bordes de la pantalla o de otros elementos, podemos usar `margin`:

```css
.texto {
  text-align: center;
  background-color: blue;
  margin: 20px;
}
```

El margen crea espacio alrededor del elemento. En este caso, habrá una separación de 20 píxeles entre la sección y los bordes externos.

También podemos redondear los bordes de esta sección:

```css
.texto {
  text-align: center;
  background-color: blue;
  margin: 20px;
  border-radius: 10px;
}
```

Con esto, el contenedor tendrá esquinas redondeadas.

Entonces, repasando lo visto en esta clase:

Aprendimos que CSS nos permite modificar la apariencia de una página HTML.

Vimos cómo seleccionar etiquetas directamente, como `body`, `h1` o `div`.

También aprendimos a usar clases para aplicar estilos solo a elementos específicos. Para seleccionar una clase en CSS, usamos un punto antes del nombre de la clase.

Además, usamos propiedades como:

```css
color
font-size
font-family
background-color
text-align
margin
border-radius
```

Estas propiedades nos permiten cambiar el color del texto, el tamaño de la fuente, la familia tipográfica, el fondo, la alineación, los márgenes y los bordes redondeados.

Con esto ya tenemos una base para empezar a darle estilo a nuestras páginas web usando CSS.

Eso sería todo por esta clase. Muchas gracias.
