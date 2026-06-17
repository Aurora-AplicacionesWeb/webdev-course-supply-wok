# Clase 4 - Introducción a CSS (Completed)

Aquí tienes la solución completa que demuestra cómo estructurar un archivo HTML vinculado a un archivo CSS externo utilizando diferentes selectores.

## Código Completo

### 1. `index.html`
```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Introducción a CSS - Completado</title>
    <!-- Vinculación del archivo CSS externo -->
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!-- Selector ID -->
    <h1 id="titulo-principal">Mi Blog de Tecnología</h1>
    
    <!-- Selector de Clase -->
    <p class="destacado">Este es un párrafo destacado que describe el propósito de este blog.</p>
    
    <!-- Selector de Etiqueta común -->
    <p>Este es un párrafo normal con información secundaria.</p>
    
    <ul>
        <li>Artículo 1</li>
        <li>Artículo 2</li>
    </ul>

</body>
</html>
```

### 2. `styles.css`
```css
/* 1. Selector de etiqueta: Aplica a todos los elementos <p> del documento */
p {
    color: #4a4a4a;
    font-size: 16px;
    line-height: 1.5;
}

/* 2. Selector de clase: Aplica solo a elementos con la clase "destacado" */
.destacado {
    font-weight: bold;
    color: #e65100; /* Naranja oscuro */
}

/* 3. Selector de ID: Aplica únicamente al elemento con id "titulo-principal" */
#titulo-principal {
    color: #1a237e; /* Azul oscuro */
    font-family: 'Arial', sans-serif;
    border-bottom: 2px solid #1a237e;
    padding-bottom: 5px;
}
```

## Conceptos Clave Demostrados
- **`<link rel="stylesheet" href="styles.css">`**: Etiqueta colocada obligatoriamente en el `<head>` que indica al navegador que debe cargar y aplicar el archivo `styles.css`.
- **Selector de etiqueta (`p`)**: Aplica a todos los elementos del mismo tipo. Muy útil para estilos generales de texto.
- **Selector de clase (`.destacado`)**: Se define con un punto previo (`.`). Permite estilizar múltiples elementos seleccionados a mano.
- **Selector de ID (`#titulo-principal`)**: Se define con un numeral (`#`). Es altamente específico y único; no se debe repetir el mismo ID en el mismo archivo HTML.
