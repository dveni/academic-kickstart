---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Zero-Shot Likes Clasiffication"
subtitle: "Ni tan fácil ni tan difícil"
summary: ""
authors: []
tags: []
categories: []
date: 2020-10-07T12:40:15+02:00
lastmod: 2020-10-07T12:40:15+02:00
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

Tras un par de semanas con este proyecto a medias (es lo que tiene el inicio de curso y de todo un poco), vuelvo a ponerme manos a la obra con él. Investigando cómo llevar a cabo la clasificación de mis tweets sin necesidad de tener datos etiquetados, llegué a [este](https://joeddav.github.io/blog/2020/05/29/ZSL.html) artículo de Joe Davison de mayo. En él, detalla distintos enfoques de problemas similares al mío, entre los que se encuentra el que voy a utilizar: "Classification as Natural Language Inference". Este método considera dos oraciones, "premisa" e "hipótesis", con la tarea de determinar si la hipótesis es correcta (confirmación) o falsa (contradicción) dadas las premisas. 

| Premise 	| Label 	| Hypothesis 	|
|-	|-	|-	|
| A man inspects the uniform of a figure in some East Asian country. 	| contradiction 	| The man is sleeping. 	|
| An older and younger man smiling. 	| neutral 	| Two men are smiling and laughing at the cats playing on the floor. 	|
| A soccer game with multiple males playing. 	| entailment 	| Some men are playing a sport. 	|

<sub>Ejemplo de http://nlpprogress.com/english/natural_language_inference.html</sub>

La idea es tratar cada tweet (oración) como "premisa" y convertir cada posible etiqueta en "hipótesis". Por lo tanto, si el modelo predice que la hipótesis "confirma" la premisa consideramos esa etiqueta como verdadera. Por suerte, el artículo te redirigía a una demo donde pude estar jugando un poco y me di cuenta de varias cosas:

1. Cómo mola [Streamlit](https://www.streamlit.io/)
2. Funciona con tweets muy bien (tampoco era tanta sorpresa)
3. Funciona con tweets en español (esto si que me sorprendió)

Jugando con la demo parecía que iba a tener todavía más fácil la tarea que me había planteado. Además, me dejaba varios caminos que llamaban mi curiosidad: ¿qué son los transformers y por qué funcionan tan bien? ¿Cómo se usa streamlit?. Y la verdad, es que encontrarme con este artículo me ha facilitado la vida. 

### Pero...

Me estoy dando cuenta de que no todo era tan sencillo como me pensaba. Ya tengo una forma de obtener mis likes y tengo una forma de clasificarlos, pero **¿cómo despliego esto?**

Esta es una pregunta para la que aún no tengo respuesta, aunque desplegar la aplicación de Streamlit sobre Heroku podría ser una buena opción. Puede que también sea una buena oportunidad para sacar Docker de la teoría y utilizarlo en la práctica.

De momento, estoy dando forma a la app de Streamlit y he tenido algunos problemillas con que PyTorch **se cargue todas las librerías que había importado anteriormente**. Pero seguimos trabajando. 


