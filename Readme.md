# Galería Joelle — metamorfosis de una vela

Ejercicio de React: una galería de posts con el tema de la metamorfosis de una vela.

## Qué hace

- Pinta una cuadrícula de tarjetas (imagen, título, descripción, contenido y fecha)
- Los datos salen de `posts.js` (`postsData`)
- Fondo e imágenes en la carpeta `img/`

## Cómo probarlo

Abre `index.html` en el navegador (carga React y Babel desde CDN, no hace falta build).

Demo: https://moussijoelle.github.io/galeria-joelle/

## Cómo lo construí

- React 18 por CDN + Babel standalone para poder escribir JSX en el HTML
- Componente `PostCard` y un `App` que hace `.map` de los posts
- Tailwind por CDN para el diseño
- Tipografía Cormorant Garamond de Google Fonts

## Cómo verificarlo

Sin tests automáticos. Abro la demo o el HTML y miro que salgan todas las tarjetas con imagen y texto.

---

Moussi Joelle  
https://github.com/moussijoelle/galeria-joelle
