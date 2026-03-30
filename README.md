# PAWPrints — TP1 (PAW) — Maquetación HTML5

## Introducción
Este repositorio contiene la resolución del *Trabajo Práctico 1* de la cursada de *PAW, cuyo objetivo es desarrollar habilidades de **maquetación de sitios web* utilizando *solo HTML5, haciendo foco en el uso correcto de **elementos semánticos* y *formularios* (sin CSS y sin lógica del lado del cliente/servidor).

El proyecto consiste en la web de una librería llamada *PAWPrints* (venta de libros), construida de forma incremental a lo largo de la cursada.  
*Nota:* este TP se arranca desde cero.


## Objetivos del TP
- Definir un *SiteMap* del sitio (jerarquía de secciones y páginas).
- Diseñar *wireframes low-fi en Figma* para las pantallas principales.
- *Maquetar el sitio* usando únicamente *HTML5*.
- Demostrar uso correcto de *semántica HTML5* (header, nav, main, section, article, footer, etc.).
- Crear un *formulario de reserva de libro* usando tipos/atributos adecuados para facilitar validación HTML.

## Estructura del proyecto
Este TP se entrega como un *proyecto único* (sitio estático HTML). La estructura sugerida es:

- README.md — este archivo (descripción del TP y consideraciones).
- autores.txt — integrantes del grupo (Nombre, Apellido, Legajo).
- index.html — página de inicio.
- catalogo.html — catálogo de libros.
- libro-*.html — páginas de detalle (una por libro) o una única página de detalle, según decisión del grupo.
- formulario.html — formulario de reserva.
- nosotros.html — acerca de nosotros.
- inicio-sesion.html — formulario para inicio de sesión.
- crear-cuenta.html —  formulario para crear una cuenta

## Cómo ejecutar / ver el sitio
Como es un sitio *solo HTML*, se puede visualizar de cualquiera de estas maneras:

1. Abrir el archivo html, por ejemplo: index.html directamente en el navegador (doble click).
2. Usar un servidor estático (opcional), por ejemplo:
   - Extensión “Live Server” en VS Code, o
   - python -m http.server y navegar a http://localhost:8000

## Decisiones de maquetación (sin CSS)
- Se prioriza el uso de *HTML semántico* para estructurar el contenido.
- Se utilizan elementos adecuados al contenido, por ejemplo:
  - header / nav para navegación
  - main como contenido principal
  - section para agrupar bloques temáticos
  - article para cada libro (tarjetas o ítems del catálogo)
  - figure / figcaption para imágenes de libros
  - address para información de contacto
  - footer con redes y datos generales

## Wireframes

- https://www.figma.com/files/team/1616609419268436800/project/575065342?fuid=1612908434420922304