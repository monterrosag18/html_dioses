# Project Atlas: Óðinn's Domain

Team: Los primordiales

World: Valhalla / Asgard

# Description

This project represents the mythological world centered exclusively on Óðinn (Odin), the Allfather. The webpage functions as a visual codex that explains his story of sacrifice, catalogs his divine artifacts (Gungnir, Sleipnir, etc.), and lists the wisdom laws from the Havamal.

# Links

Repository: (https://github.com/edwar198720Arthas/WorldHub-Crisis-en-el-Atlas-de-Crudzaso.git)
Published Site: (https://github.com/edwar198720Arthas)

# Used HTML Semantics

To comply with Crudzaso standards and accessibility, we have utilized the following:
Tag	Usage in the Project.

<header>	Contains the main title "Óðinn" and the global navigation.
<nav>	Groups the main links (#origin, #treasures, #laws), allowing users to jump between sections.
<main>	Delimits the primary and unique content about Odin, excluding the header and footer.
<article>	Used for each artifact "Card" (Gungnir, Draupnir, etc.), as they are independent pieces of content.
<aside>	Container for the fun fact/curiosity at the end, tangential to the main content.
<footer>	Legal information, team credits, and repository links.

# Branch Strategy (Git)

To avoid conflicts and facilitate teamwork, we follow this structure:

    main: The primary branch, only contains functional and tested code.

    feature/structure: Creation of index.html and semantic tags.

    feature/styles: Configuration of styles.css, color variables, and fonts.

    feature/content-odin: Drafting of texts regarding artifacts and rules.

    feature/responsive: Media Queries adjustments for mobile and desktop.

Each member works on their branch and performs a Merge via Pull Requests.

---

# Anubis - Guardian of Shadows

**Autor:** Carlos Andres Monterrosa Gallego  

## ¿De qué va esto?

Anubis es mi aporte al proyecto. Básicamente armé una página web sobre un mundo místico inspirado en Anubis, el guardián egipcio. Es un mundo liminal donde las almas pasan por juicios y pruebas, todo ambientado en corredores oscuros y rituales bajo la luna.

## Lo que tiene la página

La página está dividida en varias secciones:

- **Intro:** Una pequeña explicación del mundo y qué lo hace especial
- **Atlas del Guardián:** Una galería con 4 tarjetas que muestran los lugares y objetos importantes (Umbral de Ébano, Balanzas de Memoria, Hermanos de la Noche, Pergaminos de Juicio)
- **Reglas del Mundo:** 5 reglas que gobiernan cómo funciona este universo
- **Curiosidades:** Datos random interesantes sobre el mundo

## Diseño visual

Le puse un tema oscuro con colores dorados que van bien con la onda egipcia de Anubis. Lo más chido son dos GIF animados que puse a los lados (uno de Anubis de noche y otro de día) que le dan un toque dinámico a la página.

Usé CSS Grid para las tarjetas y me aseguré de que se vea bien en diferentes pantallas:
- En desktop se ven 4 columnas de tarjetas
- En tablets 2 columnas
- En móvil solo 1 columna para que no se vea apretado

## Estructura de archivos

```
anubis.html          <- La página principal
css/anubis.css       <- Todos los estilos
imagenes/anubis/     <- Los GIF y las imágenes de las tarjetas
```

## Etiquetas HTML que usé

Traté de usar etiquetas semánticas apropiadas:
- `<header>` para el encabezado con navegación
- `<nav>` para los links de navegación  
- `<main>` para todo el contenido principal
- `<section>` para cada sección (intro, atlas, reglas)
- `<article>` para cada tarjeta individual
- `<aside>` para las curiosidades
- `<footer>` para mis datos al final

## Responsive

La página se adapta sola a diferentes tamaños de pantalla. En móviles las imágenes laterales desaparecen para darle más espacio al contenido. También reduje los tamaños de fuente y cambié el layout del header para que quepa todo bien.

## CSS destacable

Algunas cosas cool que hice con CSS:
- Variables CSS para manejar anchos y espaciados fácilmente
- Position sticky en el header para que se quede arriba al scrollear
- Efectos hover en las tarjetas (se elevan y les aparece sombra)
- Un pseudo-elemento ::after en las imágenes laterales para crear un efecto de reflejo
- Media queries para 5 breakpoints diferentes (1400px, 1100px, 900px, 720px, 520px)

---

Made with steel and code by the team The Raven's Sons - 2025