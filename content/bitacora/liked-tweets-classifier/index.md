---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "¿Qué me gusta en Twitter?"
subtitle: "Adios al cajón de sastre"
summary: ""
authors: []
tags: ["machine learnig", "social networks"]
categories: []
date: 2020-09-11T23:09:19+02:00
lastmod: 2020-09-11T23:09:19+02:00
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

Una idea que me lleva rondando algún tiempo, Lo-Fi beats en los aurículares y puede que la noche de viernes menos entretenida del 2020, que ya es decir. Al menos de momento. Hace tiempo que mi lista de me gustas se convirtió en una mezcla de memes, videos graciosos, pelis/series que quiero ver, cosas que quiero leer, recursos interesantes y proyectos relacionados con la inteligencia artificial. Vamos, un cajón donde meto un poco de todo lo que creo que me puede interesar en algún momento pero que realmente muy pocas veces revisito. Y ya, ya sé que se pueden guardar tweets en listas o hay aplicaciones estilo Pocket, que ya uso, para guardar y clasificar este tipo de cosas. Pero, ¿por qué hacer dos o tres clicks pudiendo dar uno solo y que se guarden y clasifiquen solos? 

Revisando un poco por encima, no he encontrado ninguna herramienta que haga algo parecido. Tampoco he buscado mucho, no te voy a engañar. Pero esto supone un ejercicio interesante. Hay multitud de trabajos académicos que basan su análisis en la clasificación automática de tweets. Sin ir más lejos, mi TFG. Pero oye, que yo quiero un servicio que me separe la lista de tweets a los que doy favoritos en pelis, artículos, chorradas, IA o cualquier otro grupo temático que aparezca. Y no me voy a dedicar a anotar un dataset a mano, así que me interesan métodos de aprendizaje no supervisado. Para ello he de explorar que posibilidades hay, aunque usar el wrapper para python de Stanford's Topic Modelling Toolbox, Topbox, es un buen punto de partida. Seguramente también sea conveniente detectar previamente el idioma de los tweets, ya que seguramente aparecerán en inglés y español.  

Obviamente un trabajo así no se hace en una sola noche, así que me conformaré con empezar a pelearme con tweetpy para conseguir mis me gustas en streaming. Ire actualizando sobre la marcha.