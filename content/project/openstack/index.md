---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Application deployed on Openstack"
summary: "Automatic deployment of an application on Openstack using Heat."
authors: []
tags: ["Openstack", "Bash", "Heat", "Cloud"]
categories: []
date: 2021-01-15T20:21:21+01:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: "https://github.com/dveni/PracticaFinalCNVR_Grupo1"
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
* Salomón Fereres Benzaquen

## Description

Development of scripts, templates and other configuration files needed to deploy automatically on an Openstack cloud using Heat orchestration services of a scalable application consisting of web servers, database, balancers and firewall.

* Three web servers hosting the web application supporting the scalable service. scalable service.
* A database designed to store application data. Note: it is not necessary for the application to use the database, but it will be necessary to demonstrate that the database is accessible from the servers.
* An administration server that will be used for service management tasks and will be the only one accessible from the outside via SSH.
* A firewall that filters traffic from the outside (north-south) and only allows access to the web servers by the clients, as well as SSH traffic to the management server by the service administrators. administrators to the management server.
* A load balancer that distributes the traffic between the different web servers.