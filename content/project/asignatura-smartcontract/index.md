---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Dapp using Smart Contracts"
summary: "A distributed application for course management based on Ethereum Smart Contracts"
authors: []
tags: ["Blockchain", "Ethereum", "Smart Contract", "Truffle suite", "React"]
categories: ["course project"]
date: 2021-01-10T09:36:14+01:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "App screenshoot"
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

links:
- name: Contract address
  url: https://rinkeby.etherscan.io/address/0xc3d22cd6fb0aab36bae82a8f99d2a5cfb22ee9e3
  icon_pack: fab
  icon: ethereum
- name: Web application
  url: https://dapp-asignatura.herokuapp.com/
  

url_code: "https://github.com/dveni/BCDA-Asignatura"
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


Development of a distributed application that uses a Smart Contract deployed on an Ethereum network, Rinkeby.

Built using React & TruffleSuite (truffle, drizzle, ganache, truffle-teams).

The dapp has been deployed here: https://dapp-asignatura.herokuapp.com/ (Login with metamask is needed)

It uses the contract Asignatura (see [here](https://gist.github.com/dveni/c2cbfe62ae7476fa8f490e8f5924f980)), deployed on Rinkeby network: https://rinkeby.etherscan.io/address/0xc3d22cd6fb0aab36bae82a8f99d2a5cfb22ee9e3

## Features
* Management of a course: create assignments and exams, students grades, etc
* Automated student registration
* Visualize students grades in each evaluation
