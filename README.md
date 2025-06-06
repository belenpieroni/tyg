# Trabajo Práctico Nº1 - Sitio Web con Consumo de APIs Públicas

Este sitio fue desarrollado como parte de la materia **Tecnología y Gestión Web**. El objetivo principal fue aplicar conceptos de HTML5 semántico, estilos con CSS3, manipulación del DOM y consumo de APIs públicas utilizando JavaScript.

## Descripción general

El sitio web cuenta con una estructura semántica clara y funcional:

- `<header>`: logo alineado a la izquierda, título del trabajo y nombre completo centrado.
- `<aside>`: barra lateral izquierda con un menú que contiene botones para consumir distintas APIs públicas.
- `<main>`: sección principal que incluye:
  - Una frase aleatoria con estilo y sombras aplicadas mediante CSS.
  - Un párrafo con mi expectativa personal sobre la materia.
  - Un área dinámica donde se muestra el contenido de las APIs.
- `<footer>`: nombre de la materia y año, alineados a la derecha.

Además, se incluye un video de fondo que le da una estética profesional y atractiva al sitio.

## Funcionalidades

- **Frase del día**: al cargar la página, se muestra una de tres frases con diferentes estilos de sombra en el texto.
- **Expectativa personal**: un párrafo con una reflexión personal sobre la materia.
- **Botones de API**:
  - **Consejo del día**: utiliza `https://api.adviceslip.com/advice` y traduce el texto al español usando la API de Google Translate.
  - **Libro recomendado**: consume datos de `https://openlibrary.org/search.json?q=book&limit=10` para mostrar un libro aleatorio con su título, autor y año de publicación.

## Tecnologías utilizadas

- **HTML5**: estructura semántica.
- **CSS3**: diseño visual, sombras de texto, video de fondo.
- **JavaScript**: lógica de selección aleatoria, consumo de APIs y actualización dinámica del contenido.
- **APIs públicas**:
  - [Advice Slip API](https://api.adviceslip.com)
  - [OpenLibrary API](https://openlibrary.org/developers/api)

## Autor
Pieroni, María Belén
Estudiante de Ingeniería en Sistemas de Información (UTN)
Trabajo realizado para la materia electiva Tecnología y Gestión Web
Año: 2025
