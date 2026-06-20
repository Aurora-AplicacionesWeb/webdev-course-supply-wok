# Guión de Clase 4 - Introducción a CSS

Este documento sirve como guía/guión para el profesor durante la demostración en vivo de la clase 4.

## Minuto a Minuto

### 1. ¿Qué es CSS?
* **Objetivo:** Explicar el concepto de separación de responsabilidades.
* **Concepto:**
  * HTML es el esqueleto de la casa (paredes, estructura).
  * CSS es la pintura, decoración, y diseño de la casa.
  * Mantenerlos separados hace que el código sea limpio y reutilizable.

### 2. Vinculando HTML y CSS
* **Acción:** Crear un archivo `styles.css` en vivo al lado de `index.html`.
* **Acción en HTML:** Agregar la etiqueta `<link>` en el `<head>`.
  ```html
  <link rel="stylesheet" href="styles.css">
  ```
* **Explicación:**
  * El atributo `rel="stylesheet"` le dice al navegador qué tipo de recurso enlazamos.
  * El atributo `href` indica la ruta relativa al archivo CSS.

### 3. Sintaxis y Selectores Básicos
* **Acción:** Escribir reglas en `styles.css` demostrando la sintaxis: `selector { propiedad: valor; }`.
* **Demostración de Selectores:**
  1. **Selector de Etiqueta (Tag selector):**
     * Escribir `p { color: gray; }`.
     * Explicar: Afecta a *todos* los párrafos de la página.
  2. **Selector de Clase (Class selector):**
     * Agregar `class="mi-clase"` a un elemento HTML.
     * Escribir `.mi-clase { color: red; }` en el CSS.
     * Explicar: Se usa un punto inicial (`.`). Sirve para grupos de elementos.
  3. **Selector de ID (ID selector):**
     * Agregar `id="mi-id"` a un elemento HTML.
     * Escribir `#mi-id { font-size: 24px; }` en el CSS.
     * Explicar: Se usa una almohadilla/numeral (`#`). Es único para un solo elemento específico de la página.

---

## Código Guía para el Instructor
```css
/*styles.css*/
h1 {
    color: darkblue;
}
.destacado {
    color: orange;
    font-weight: bold;
}
#mi-unico-parrafo {
    text-decoration: underline;
}
```
```html
<!-- index.html -->
<h1 id="mi-titulo">Hola Mundo</h1>
<p class="destacado">Párrafo destacado con estilo naranja.</p>
<p>Párrafo común.</p>
<p id="mi-unico-parrafo">Párrafo único subrayado.</p>
```
