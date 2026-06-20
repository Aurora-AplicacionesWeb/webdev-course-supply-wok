# Clase 8 - Recomendaciones y errores comunes (Completed)

Aquí tienes los 5 errores más comunes de principiantes, cada uno con el código incorrecto, el código corregido y por qué importa.

## 1. Etiquetas sin cerrar

```html
<!-- ❌ Incorrecto -->
<p>Hola mundo
<p>Otro párrafo

<!-- ✅ Correcto -->
<p>Hola mundo</p>
<p>Otro párrafo</p>
```

**Por qué importa:** el navegador no marca error — simplemente "adivina" dónde termina cada elemento, y el diseño se rompe en cascada para todo lo que sigue.

## 2. Nombres de archivo

```text
❌ Mi Pagina.HTML
❌ FotoPerfil.JPG

✅ mi-pagina.html
✅ foto-perfil.jpg
```

**Por qué importa:** minúsculas, sin espacios, con guiones. Mayúsculas y espacios rompen enlaces en muchos servidores, aunque en tu computadora funcione bien.

## 3. CSS mal vinculado

```html
<!-- ❌ Incorrecto: falta rel="stylesheet" -->
<link href="estilo.css">

<!-- ✅ Correcto -->
<link rel="stylesheet" href="estilo.css">
```

**Por qué importa:** sin `rel="stylesheet"` no hay error visible — el CSS simplemente no carga y la página se ve sin ningún estilo.

## 4. Código desordenado (sin indentación)

```html
<!-- ❌ Incorrecto -->
<div>
<p>Texto</p>
<ul><li>Item</li>
</ul></div>

<!-- ✅ Correcto -->
<div>
  <p>Texto</p>
  <ul>
    <li>Item</li>
  </ul>
</div>
```

**Por qué importa:** no afecta el funcionamiento, pero el orden te permite encontrar tus propios errores más rápido.

## 5. Selectores que no aplican

```html
<!-- ❌ Incorrecto: "Titulo" vs ".titulo" no coinciden -->
<p class="Titulo">Texto</p>
```
```css
.titulo { color: teal; }
```

```html
<!-- ✅ Correcto -->
<p class="titulo">Texto</p>
```
```css
.titulo { color: teal; }
```

**Por qué importa:** CSS distingue mayúsculas de minúsculas. `"Titulo"` y `"titulo"` son nombres distintos — mantén siempre la misma escritura entre HTML y CSS.

## Recursos para seguir aprendiendo

- **[MDN Web Docs](https://developer.mozilla.org/es/)** — documentación oficial de HTML y CSS, en español.
- **[W3C Validator](https://validator.w3.org/)** — valida tu código y te dice exactamente qué etiqueta está mal cerrada.
- **Consola del navegador** — clic derecho → Inspeccionar → Console, casi siempre da pistas del error.
