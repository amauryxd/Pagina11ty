---
layout: base.njk
title: Blog de Amaury
---

# {{ title }}

## Artículos

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