# Clase 4 - Introducción a CSS (Starter)

En esta clase aprenderemos a conectar una hoja de estilos externa a nuestro documento HTML y a escribir los primeros selectores básicos.

## Código Inicial

### 1. `index.html` (Starter)
```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Introducción a CSS</title>
    
    <!-- TODO: 1. Vincula aquí el archivo styles.css usando la etiqueta <link> -->
    
</head>
<body>

    <h1 id="titulo-principal">Mi Blog de Tecnología</h1>
    
    <p class="destacado">Este es un párrafo destacado que describe el propósito de este blog.</p>
    
    <p>Este es un párrafo normal con información secundaria.</p>
    
    <ul>
        <li>Artículo 1</li>
        <li>Artículo 2</li>
    </ul>

</body>
</html>
```

### 2. `styles.css` (Starter)
```css
/* TODO: 2. Crea los siguientes selectores en este archivo */

/* A. Selector por etiqueta (afecta a todos los párrafos 'p') */

/* B. Selector por clase (afecta a elementos con class="destacado") */

/* C. Selector por ID (afecta al elemento con id="titulo-principal") */
```

## Instrucciones de Práctica
1. Vincula la hoja de estilos en la cabecera HTML usando:
   `<link rel="stylesheet" href="styles.css">`.
2. En el archivo `styles.css`:
   - Agrega un selector de etiqueta `p` para cambiar el color del texto a gris oscuro (`#333333`).
   - Agrega un selector de clase `.destacado` para poner el texto en negrita (`font-weight: bold`).
   - Agrega un selector de ID `#titulo-principal` para cambiar su color a azul marino o verde oliva.
