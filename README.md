# Recetario Digital Guayusana

Este es el repositorio del recetario digital para "Guayusana", una bebida energizante natural a base de guayusa. La página está diseñada para ser accedida a través de un código QR en los envases del producto, ofreciendo a los usuarios un lugar para descubrir nuevas recetas y formas de disfrutar su bebida.

## Tecnologías Utilizadas

Este es un sitio web estático construido con:

-   **HTML5:** Para la estructura y el contenido semántico.
-   **CSS3:** Para el diseño, la responsividad y los estilos visuales. Los estilos están organizados en múltiples archivos para mayor legibilidad y mantenimiento.

No se utilizan frameworks de CSS ni librerías de JavaScript.

## Estructura del Proyecto

El proyecto tiene la siguiente estructura de archivos:

```
Guayusana-page/
├── index.html
├── README.md
├── assets/
│   └── guayusana.jpeg
└── css/
    ├── styles.css
    ├── base.css
    ├── responsive.css
    └── components/
        ├── header.css
        ├── sections.css
        ├── cards.css
        ├── forms.css
        └── footer.css
```

-   `index.html`: Contiene toda la estructura y contenido de la página.
-   `css/styles.css`: Archivo principal de estilos que importa todos los demás archivos de CSS.
-   `css/components/`: Directorio que contiene los archivos de CSS separados por componente (header, footer, etc.).
-   `assets/`: Contiene los recursos de imágen.
-   `README.md`: Este mismo archivo, que proporciona información sobre el proyecto.

## Cómo Usarlo

Para ver la página web, simplemente abre el archivo `index.html` en tu navegador de preferencia (por ejemplo, haciendo doble clic en él).

Para un desarrollo más avanzado, puedes usar una extensión de servidor en vivo en tu editor de código (como "Live Server" en VS Code) para ver los cambios reflejados en tiempo real.

## Personalización

Puedes personalizar fácilmente varios aspectos del sitio.

### Colores y Estilos Globales

Los colores principales y los estilos globales (tipografía, espaciado) están definidos como variables CSS en el archivo `css/components/base.css`. Puedes cambiar estos valores para alterar la paleta de colores de todo el sitio.

```css
/* css/components/base.css */
:root {
    --verde-intenso: #2E7D32;
    --amarillo-suave: #FFFDE7;
    --blanco-tarjeta: #FFFFFF;
    --texto-principal: #333333;
    --verde-spotify: #1DB954;
}
```

### Añadir o Editar Recetas

Las recetas se encuentran en la sección con `id="recetas"` dentro de `index.html`. Cada receta es un `<article class="recipe-card">`. Para añadir una nueva, simplemente copia y pega uno de estos artículos y modifica su contenido.

### Enlace de la Playlist de Spotify

El enlace a la playlist de Spotify se encuentra en la sección con `id="playlist"` en `index.html`. Busca el `<a>` con la clase `btn-spotify` y reemplaza la URL en el atributo `href`.

## Créditos

**Guayusana** es un concepto de bebida energizante, natural y personalizable, inspirada en la riqueza de la guayusa de Ecuador y la cultura amazónica. Este proyecto busca reflejar esa identidad en una experiencia digital fresca y motivadora.