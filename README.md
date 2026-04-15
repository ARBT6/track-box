# TrackBox

Página de reproducción de música con buscador integrado. Busca cualquier canción o artista y escucha un preview de 30 segundos directamente desde el navegador, sin registro ni suscripción.

## Funcionalidades

- Buscador de canciones conectado a la API de iTunes
- Preview de 30 segundos por canción encontrada
- Tracks destacados de artistas independientes disponibles de forma local

## API de iTunes

La búsqueda utiliza la [iTunes Search API](https://performance-partners.apple.com/search-api) de Apple. Al buscar una canción o artista, la app consulta el endpoint público de iTunes y muestra los resultados con portada, título, artista y un reproductor de audio con el preview de 30 segundos que provee Apple de forma gratuita.

No requiere autenticación ni API key.

## Tracks destacados (locales)

- **Appearing Nowhere** — Zenith Bikini ft. Rusty James Miller
- **Back To The Start** — Patrick Jordan Patrikios
- **Willow Gozilla** — Zenith Bikini ft. Rusty James Miller

## Tecnologías

- HTML5
- CSS3
- JavaScript (Fetch API)
- iTunes Search API
- Audio nativo del navegador (`<audio>`)

## Uso

Abre `index.html` en cualquier navegador moderno. Usa el buscador para encontrar cualquier canción y reproducir su preview de 30s, o elige uno de los tracks destacados.
