# Técnico en Casa – Guía Interactiva para Reparación de Grifería

Sitio web educativo que explica cómo cambiar un o'ring en una canilla paso a paso. Incluye contenido visual, herramientas necesarias, instrucciones detalladas y una encuesta de feedback.

---

## 🚀 Objetivo

Ayudar a cualquier persona a realizar una reparación básica del hogar sin necesidad de conocimientos previos de plomería.

---

## 🧠 Mejoras y correcciones realizadas

Este proyecto partió de un documento base que fue corregido, ordenado y optimizado por mí. A continuación, detallo los cambios principales:

### 🧱 Estructura HTML:
- ✅ Eliminación de etiquetas inválidas como `<p2>` y `<class="h2">`.
- ✅ Reorganización de listas (`<ol>`, `<ul>`) con estructura semántica correcta.
- ✅ Inclusión de `id` en las secciones para navegación interna (`herramientas`, `procedimiento`, `encuesta`).
- ✅ Inclusión de un `nav` funcional con enlaces internos.
- ✅ Incorporación de un `footer` limpio y funcional.

### 🎨 Correcciones y mejoras en CSS:
- ✅ Cambio de colores `rgba()` a valores hexadecimales con opacidad (`#000000b2`, `#ffffff40`).
- ✅ Reemplazo de nombres de clase como `.h2` y `.h3` por etiquetas semánticas.
- ✅ Simplificación del `header`, eliminando propiedades innecesarias (`flex` innecesario, `height` redundante).
- ✅ Uniformización de `padding` y `margin` en todas las secciones para armonía visual.
- ✅ Alineación de listas ordenadas: texto alineado a la izquierda pero bloque centrado.
- ✅ Implementación de `hover` funcional para mostrar imágenes al pasar el mouse sobre cada botón.
- ✅ Corrección de `margin: absolute;` inválido.
- ✅ Creación de clases reutilizables como `.separador` para espaciado visual con fondo personalizado.

---

## 📦 Contenido del sitio

### 🔸 Header
- Título llamativo sobre imagen de fondo
- Tipografía personalizada (`Share Tech`)

### 🔸 Navegación
- Enlaces internos con scroll inmediato a:
  - Herramientas
  - Procedimiento
  - Encuesta

### 🔸 Herramientas
- Lista de herramientas con botones
- Imágenes visibles al pasar el mouse

### 🔸 Procedimiento
- Pasos detallados en lista ordenada `<ol>`
- Centrado del bloque con texto alineado a la izquierda
- Mejoras en jerarquía visual

### 🔸 Encuesta
- Formulario con campos requeridos (nombre y email)
- Radio buttons para que solo se pueda elegir una opción
- Campo para comentarios y opinión sobre herramienta más útil
- Estilo coherente con el resto del sitio

### 🔸 Video embebido
- Video de YouTube centrado dentro de un contenedor
- Estética consistente con el diseño general

### 🔸 Footer
- Enlaces a Instagram y WhatsApp
- Derechos reservados en texto pequeño debajo

---

## 🧰 Tecnologías utilizadas

- HTML5
- CSS3 (Flexbox, pseudo-clases, unidades relativas)
- Google Fonts
- YouTube embed

---

## 📋 Cómo visualizarlo

1. Cloná el repositorio:

   ```bash
   git clone https://github.com/tuusuario/tecnico-en-casa.git
