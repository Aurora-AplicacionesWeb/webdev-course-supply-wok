# Guión de Clase 3 - Elementos HTML Comunes (12 minutos)

Este documento sirve como guía/guión para el profesor durante la demostración en vivo de la clase 3.

## Minuto a Minuto

### 1. Introducción al Contenido (2 minutos)
* **Objetivo:** Explicar cómo agregar texto con formato, agrupaciones y multimedia al esqueleto creado en la Clase 2.
* **Concepto:**
  * HTML no es solo "colocar texto", requiere etiquetas semánticas para que el navegador y los buscadores entiendan qué es cada cosa.

### 2. Jerarquía de Textos (3 minutos)
* **Acción:** Escribir un título `<h1>` y un subtítulo `<h2>`.
* **Explicación:**
  * `<h1>` es el título principal. Regla de oro: **Solo debe haber un `<h1>` por página.**
  * `<h2>` a `<h6>` se usan para subsecciones de menor importancia jerárquica.
  * `<p>` se usa para párrafos comunes de texto continuo.

### 3. Listas (3 minutos)
* **Acción:** Escribir una lista de habilidades usando `<ul>` y `<li>`.
* **Explicación:**
  * `<ul>` significa *Unordered List* (Lista Desordenada). Muestra viñetas.
  * `<ol>` significa *Ordered List* (Lista Ordenada). Muestra números correlativos.
  * Ambas requieren de ítems internos `<li>` (*List Item*).

### 4. Enlaces e Imágenes (4 minutos)
* **Acción:** Insertar una etiqueta `<a>` y una etiqueta `<img>`.
* **Explicación:**
  * `<a>` (*Anchor*): Usa el atributo `href` para definir la URL destino. Se explica el atributo opcional `target="_blank"` para abrirlo en nueva pestaña.
  * `<img>` (*Image*): Es autocerrada (no lleva `</img>`). Tiene `src` para la ruta y `alt` para la descripción de accesibilidad (crucial para lectores de pantalla y si falla la carga de la imagen).

---

## Código Guía para el Instructor (Copiar y pegar rápido)
```html
<h1>Mi Perfil</h1>
<p>Hola, bienvenido a mi sitio de práctica.</p>
<h3>Mis Intereses</h3>
<ul>
    <li>Programar en C#</li>
    <li>Diseñar interfaces</li>
    <li>Aprender Webdev</li>
</ul>
<a href="https://dotnetfiddle.net/">Ir a DotNetFiddle</a>
<br><br>
<img src="https://images.unsplash.com/photo-1542831371-29b0f74f9713?w=500" alt="Código en pantalla" width="300">
```
