# Clase 2 - Estructura y Desarrollo HTML (Starter)

Este documento sirve como guía para el profesor durante la demostración en vivo de la clase 2.

### HTML

También conocido como: **HyperText Markup Language** o **Lenguaje de Marcado de Hipertexto**, es el lenguaje que define la estructura de una web. Funciona con etiquetas, las cuales funcionan como cajas contenedoras. Tenemos que pensar en ellas como etiquetas de equipaje: le dicen al navegador que hay dentro.

### Etiquetas HTML de ejemplo

- `<button>`: Etiqueta de apertura para construir un construir un botón.
- `</button>`: Etiqueta de cierre para la construcción de un botón.
- `<a href="https://www.google.com">`: Etiqueta que nos permite crear una dirección de enlace.
- `href="https://www.google.com"`: Atributo que nos permite indicarnos a que URL debe dirigirse el enlace.

### Construcción del Esqueleto HTML

````html
<<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Mi Primera Página</title>
</head>
<body>
  <h1>¡Hola Mundo!</h1>
  <p>Bienvenidos a mi primer sitio web.</p>
</body>
</html>
````

### Conceptos Clave

- **`<!DOCTYPE html>`**: Etiqueta que le avisa al navegador que estamos usando la versión más moderna de HTML (HTML5).

- **`<html>`**: Etiqueta raíz que envuelve todo nuestro proyecto HTML.

- **`<head>`**: Etiqueta donde se almacena la información invisible al usuario, pero importante (metadatos), como el título de la pestaña (`<title>`) o el idioma.

- **`<meta charset="UTF-8">`**: Etiqueta que nos indica en que idioma estamos trabajando.

- **`<title>`**: Etiqueta que nos indica el título de la pestaña donde está alojada nuestro sitio web.

- **`<body>`**: Etiqueta que representa el cuerpo de la página web. Todo lo que pongamos aquí dentro es lo que el usuario final va a ver en la pantalla. Ponemos un título (`<h1>`) y un párrafo (`<p>`).

