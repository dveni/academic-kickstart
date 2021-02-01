---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Distributed Hash Table"
summary: "Built in Java using Zookeeper"
authors: []
tags: ["Java", "Zookeeper"]
categories: ["course project"]
date: 2020-11-23T20:17:44+01:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "DHT Architecture"
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: "https://github.com/dveni/DHT_Zookeeper"
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
## Authors
* Raúl Torres García
* Daniel Vera Nieto
* Salomón Fereres

## Description

Distributed application managing a Distributed Hash Table with a global table divided into partitions, storing each partition in different servers of the distributed application. Each server manages a partition of the global table, which holds a range of values in hash function space (the size of the range is the same for each node). The servers have information that relates the partition of the data to the IP address of the server that manages the corresponding table.

## Features

* Availability, consistency and fault tolerance properties are based on Zookeeper.
* When a server is down, a new server is created to replace it and allow the application to continue to function. Updated tables are sent to the new server.
* An objectively ugly basic GUI.