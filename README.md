# Recetario Digital Guayusana

Este es el repositorio del recetario digital para "Guayusana", una bebida energizante natural a base de guayusa. La página está diseñada para ser accedida a través de un código QR en los envases del producto, ofreciendo a los usuarios un lugar para descubrir nuevas recetas y formas de disfrutar su bebida.

## Tecnologías Utilizadas

Este es un sitio web estático construido exclusivamente con:

-   **HTML5:** Para la estructura y el contenido semántico.
-   **CSS3:** Para el diseño, la responsividad y los estilos visuales, todo integrado en el propio archivo HTML.

No se utilizan frameworks de CSS, librerías de JavaScript ni archivos externos.

## Estructura del Proyecto

El proyecto consta de dos archivos principales en la raíz:

-   `index.html`: Contiene toda la estructura, contenido y estilos de la página web.
-   `README.md`: Este mismo archivo, que proporciona información sobre el proyecto.

## Cómo Usarlo

Para ver la página web, simplemente abre el archivo `index.html` en tu navegador de preferencia (por ejemplo, haciendo doble clic en él).

Para un desarrollo más avanzado, puedes usar una extensión de servidor en vivo en tu editor de código (como "Live Server" en VS Code) para ver los cambios reflejados en tiempo real.

## Personalización

Puedes personalizar fácilmente varios aspectos del sitio directamente en el archivo `index.html`:

### Colores y Estilos

Los colores principales están definidos como variables CSS al inicio del bloque `<style>` en el `<head>`. Puedes cambiar estos valores para alterar la paleta de colores de todo el sitio.

```css
:root {
    --verde-intenso: #2E7D32;
    --amarillo-suave: #FFFDE7;
    --blanco-tarjeta: #FFFFFF;
    --texto-principal: #333333;
    --verde-spotify: #1DB954;
}
```

### Añadir o Editar Recetas

Las recetas se encuentran en la sección con `id="recetas"`. Cada receta es un `<article class="recipe-card">`. Para añadir una nueva, simplemente copia y pega uno de estos artículos y modifica su contenido:

-   El nombre de la receta (`<h3>`).
-   Las etiquetas (`<span class="badge">`).
-   La lista de ingredientes (`<ul>`).
-   Los pasos de preparación (`<ol>`).
-   El "Tip del creador" (`<p>`).

### Enlace de la Playlist de Spotify

El enlace a la playlist de Spotify se encuentra en la sección con `id="playlist"`. Busca el siguiente bloque de código y reemplaza la URL de ejemplo (`https://open.spotify.com/playlist/XXXXXXXXX`) por el enlace real de tu playlist.

```html
<!-- IMPORTANTE: Reemplaza la URL de ejemplo de abajo por el enlace real de tu playlist de Spotify -->
<a href="https://open.spotify.com/playlist/XXXXXXXXX" class="btn btn-spotify" target="_blank">
    Escuchar playlist en Spotify
</a>
```

## Créditos

**Guayusana** es un concepto de bebida energizante, natural y personalizable, inspirada en la riqueza de la guayusa de Ecuador y la cultura amazónica. Este proyecto busca reflejar esa identidad en una experiencia digital fresca y motivadora.
