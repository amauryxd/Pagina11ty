---
layout: base.njk
title: Blog de Amaury
---

# {{ title }}

![Header]({{ './static/img/pg1.png' | url }})

## Acerca de mi

Soy un estudiante de Ingeniería en Software Interactivo y Videojuegos, tengo conocimiento en areas como:
 - 💻Programación
    - C#
    - Java
    - JavaScript
 - 🎮Diseño de juegos
    - Diseño de niveles
    - Mecanicas
    - Planeación
 - 🎹Música
    - Composición
    - Interpretación
    - FL studio 
 - 🎞️Edición de video
    - DaVinci Resolve 
    - Magix Video Deluxe
 - 📷Edición de Imagen
    - Photoshop
## Articulos

### Categoría Artistas

{% for artista in collections.artistas %}

- [{{artista.data.title}}]({{ artista.url | url }})

{% endfor %}

### Categoria Animes

{% for anime in collections.animes %}

- [{{anime.data.title}}]({{ anime.url | url }})

{% endfor %}

### Categoria Videojuegos

{% for videojuego in collections.videojuegos %}

- [{{videojuego.data.title}}]({{ videojuego.url | url }})

{% endfor %}