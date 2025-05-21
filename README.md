# 📄 Ejercicios de HTML5: Semántica, Multimedia, Formularios, Accesibilidad y Navegación

Este proyecto contiene tres ejercicios diseñados para practicar el uso correcto de etiquetas semánticas de HTML5, elementos multimedia, formularios, tablas accesibles, navegación con íconos y estilos en línea. Está orientado al desarrollo de páginas web accesibles, funcionales y organizadas.

---

## ✅ Ejercicio 1: Página Semántica con Multimedia y Formulario

### 🎯 Objetivo

Practicar el uso de etiquetas **semánticas**, insertar elementos **multimedia** e implementar un **formulario funcional** con validación básica.

### 🧩 Requisitos

* Estructura semántica usando:

  ```html
  <header>, <nav>, <main>, <section>, <article>, <footer>
  ```
* Un video incrustado usando la etiqueta `<video>` (puede ser de un archivo local o un enlace externo).
* Un formulario que contenga:

  * Campo de **nombre** (`<input type="text">`)
  * Campo de **email** (`<input type="email">`)
  * Campo de **edad** (`<input type="number">`)
  * Botón de **envío** (`<input type="submit">`)
* Atributos recomendados: `required`, `placeholder`
* Un **mapa de imagen simple** con un área que enlace a una página externa.

---

## ✅ Ejercicio 2: Tabla Accesible y Lista Anidada

### 🎯 Objetivo

Practicar la creación de **tablas accesibles**, uso de **listas anidadas** y aplicación de **estilos en línea** sin usar CSS externo.

### 🧩 Requisitos

* Tabla que represente un **horario de clases** con al menos:

  * 3 días
  * 4 bloques de horario
  * Uso de `<th>` para encabezados y `<caption>` como título de la tabla
  * Incorporación de atributos ARIA como `aria-label`
* Una **lista anidada** debajo de la tabla (por ejemplo, cursos y sus subtemas).
* Aplicación de estilos en línea como:

  ```html
  style="border: 1px solid black; background-color: #d4efff;"
  ```

---

## ✅ Ejercicio 3: Navegación con Íconos y Citas

### 🎯 Objetivo

Diseñar una **barra de navegación horizontal** con enlaces, incluir **íconos** y utilizar **etiquetas semánticas** de texto.

### 🧩 Requisitos

* Barra de navegación con enlaces a secciones ficticias:

  * "Inicio", "Blog", "Contacto", "Acerca de"
  * Implementada con `<ul>` y `<li>`, con estilos en línea
* Al menos **dos íconos** usando **Font Awesome** o imágenes locales:

  * Ejemplo: lupa (🔍) para búsqueda, correo (✉️) para contacto
* En la sección principal:

  * Una **cita** usando `<blockquote>` con el atributo `cite`
  * Texto con etiquetas semánticas como `<strong>`, `<em>`, y `<mark>`

---

## 🧱 Tecnologías y Etiquetas Clave

* **HTML5 Semántico:** `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`
* **Multimedia:** `<video>`, `<img usemap>`, `<map>`, `<area>`
* **Formularios:** `<form>`, `<input type="text/email/number/submit">`, `required`, `placeholder`
* **Tablas:** `<table>`, `<tr>`, `<th>`, `<td>`, `<caption>`, `aria-label`
* **Listas:** `<ul>`, `<li>`, listas anidadas
* **Texto Semántico:** `<strong>`, `<em>`, `<mark>`, `<blockquote cite="">`
* **Iconos:** Font Awesome (`<i class="fas fa-search">`)
* **Estilos en Línea:** Atributo `style` en HTML
