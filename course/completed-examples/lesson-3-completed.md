# Clase 3 - Elementos HTML Comunes (Completed)

Aquí tienes la solución completa de la Clase 3 mostrando el uso correcto de encabezados, párrafos, listas, imágenes y enlaces.

## Código Completo

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Perfil Profesional</title>
</head>
<body>

    <!-- Jerarquía de textos -->
    <h1>John Doe</h1>
    <h2>Desarrollador Web Junior</h2>
    <p>¡Hola! Soy un apasionado por la tecnología y la creación de interfaces web atractivas y funcionales. Actualmente estoy aprendiendo HTML, CSS y JavaScript.</p>
    
    <hr>

    <!-- Listas de habilidades -->
    <h3>Mis Habilidades Técnicas</h3>
    <ul>
        <li>Maquetación HTML5 y CSS3</li>
        <li>Control de versiones con Git & GitHub</li>
        <li>Fundamentos de programación</li>
    </ul>

    <!-- Medios y Enlaces -->
    <h3>Mi Lugar Favorito para Estudiar</h3>
    <p>
        Suelo utilizar la documentación oficial de MDN para resolver dudas y seguir creciendo. Puedes visitarla en el siguiente enlace:
    </p>
    <p>
        <a href="https://developer.mozilla.org/" target="_blank">Visitar MDN Web Docs</a>
    </p>

    <!-- Imagen ilustrativa -->
    <img src="https://images.unsplash.com/photo-1542831371-29b0f74f9713?w=500&auto=format&fit=crop&q=60" alt="Código de programación en pantalla" width="400">

</body>
</html>
```

## Conceptos Clave Demostrados
- **`<h1>` a `<h3>`**: Permiten organizar el contenido jerárquicamente. Ayuda al SEO y a la legibilidad.
- **`<ul>` y `<li>`**: Estructura de lista desordenada ideal para enumerar características sin un orden particular.
- **`<a>`**: Enlace con atributo `target="_blank"` para abrir la página en una nueva pestaña sin sacar al usuario del sitio actual.
- **`<img>`**: Etiqueta autocerrada que utiliza `src` (ruta/URL de la imagen) y `alt` (texto alternativo de accesibilidad).
