# Guión de Clase 8 - Recomendaciones y errores comunes

Este documento sirve como guía/guión para el instructor durante la grabación de la clase 8. Formato: sin cámara, voz en off sobre PPT compartido en pantalla.

## Minuto a Minuto

### 1. Gancho 

* **Objetivo:** Enganchar al estudiante explicando que una página puede verse bien y aun así tener errores invisibles.
* **Guión:**
  > "Llegaste hasta acá, y eso significa que ya tienes tu propia página web hecha con HTML y CSS. Felicidades, en serio. Pero quiero contarte algo que casi nadie te dice cuando empiezas: tu página puede verse bien... y aun así tener errores escondidos. Errores que el navegador no te marca, no te avisa, no te explica. En los próximos minutos vamos a ver los 5 errores más comunes que comete cualquier principiante — yo los cometí todos — y cómo evitarlos."
* **Slide:** roadmap de 5 errores.

### 2. Error 1: Etiqueta sin cerrar

* **Acción:** Mostrar slide con código `❌` y `✅`.
* **Guión:**
  > "Empecemos con el más común: olvidar cerrar una etiqueta. Mira este código: `<p>Hola mundo`. El navegador no te tira un error en rojo. HTML es flexible, así que adivina dónde debería terminar ese párrafo — y a veces adivina mal. La versión correcta es `<p>Hola mundo</p>`. Por cada etiqueta que abres, hay una que cierra. Un solo cierre olvidado puede desordenar todo lo que sigue."

### 3. Error 2: Nombres de archivo

* **Acción:** Mostrar slide `Mi Pagina.HTML` vs `mi-pagina.html`.
* **Guión:**
  > "Segundo error: cómo nombras tus archivos. En tu computadora `Mi Pagina.HTML` abre perfecto. Pero al subirlo a un servidor o GitHub, muchos distinguen mayúsculas de minúsculas, y los espacios rompen el enlace. La forma correcta: todo minúsculas, sin espacios, con guion medio."

### 4. Error 3: CSS mal vinculado

* **Acción:** Mostrar slide `<link href="style.css">` vs `<link rel="stylesheet" href="style.css">`.
* **Guión:**
  > "Tercer error, el más silencioso de todos. Falta `rel="stylesheet"`. Sin eso, el navegador no sabe que es una hoja de estilos y no la carga — sin ningún mensaje de error. Tu página simplemente se ve sin estilos, como si el CSS nunca hubiera existido."

### 5. Error 4: Indentación caótica

* **Acción:** Mostrar slide código pegado vs código ordenado.
* **Guión:**
  > "Cuarto error: este no rompe tu página, te rompe a ti. Funciona igual de bien para el navegador. Pero sin indentación es casi imposible ver qué etiqueta está dentro de cuál. La indentación es para ti: te ayuda a encontrar tus propios errores en segundos, no en minutos."

### 6. Error 5: Selectores que no aplican

* **Acción:** Mostrar slide `class="Titulo"` / `.titulo` vs corregido.
* **Guión:**
  > "Quinto y último error: CSS distingue mayúsculas de minúsculas en los nombres de clases. La clase en el HTML es `Titulo`, con T mayúscula. Pero en el CSS escribiste `.titulo`, todo en minúscula. Para CSS son dos nombres completamente distintos — no coinciden, y el estilo simplemente no se aplica. La solución: elegir una convención y respetarla siempre."

### 7. Recursos + cierre

* **Acción:** Mostrar capturas de MDN Web Docs y W3C Validator, luego slide de cierre con CTA.
* **Guión:**
  > "Para cerrar, tres lugares a los que acudir cuando te atasques. El primero, MDN Web Docs: documentación oficial de HTML y CSS, con versión en español y ejemplos para cada etiqueta. El segundo, el Validador del W3C: le pegas tu código y te dice línea por línea qué falta. Y el tercero, el más rápido: clic derecho en tu navegador, Inspeccionar, pestaña Console. Con esto terminamos el curso completo. Tu último paso: comparte tu Profile Card en el formulario que está en la descripción de este video. Gracias por llegar hasta el final — nos vemos en el próximo proyecto."

---

## Código guía para el instructor (referencia rápida)

```html
<!-- Error 1 -->
<p>Hola mundo</p>

<!-- Error 3 -->
<link rel="stylesheet" href="estilo.css">

<!-- Error 5 -->
<p class="titulo">Texto</p>
```
```css
.titulo { color: teal; }
```
