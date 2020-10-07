---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Avances en el Tweet Classification project"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2020-09-12T23:17:41+02:00
lastmod: 2020-09-12T23:17:41+02:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

No sé si es la vuelta de las vacaciones o que estoy empanado (puede que un poco de ambas), pero que Twitter haya actualizado su API me está dando más dolores de cabeza de los que pensaba. Toca hacerse a la nueva API. Por desgracia, parece que tweetpy sigue utilizando la API anterior que, aunque funciona actualmente, será sustituida por la nueva en el futuro. Y no quiero tener que actualizar una aplicación sencilla a los dos meses.

* Una hora más tarde: Cambio de opinión, pelearme con la nueva API de twitter para realizar la autenticación y el resto a mano está *out of scope*. Cuando tweepy actualice su librería será un buen momento para actualizar este pequeño proyecto si por entonces aún lo creo necesario.

* Acabamos el día (noche) y ya tengo guardados en un dataframe todos los tweets a los que he dado like. Los próximos pasos serás 1) construir el clasificador, 2) actualizar la lista de tweets según vaya dando like a nuevos tweets, y 3) publicar la app usando streamlit o algo similar.


