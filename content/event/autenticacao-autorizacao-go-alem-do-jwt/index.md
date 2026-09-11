---
title: "Autenticação e Autorização em Go além do JWT"

draft: false

event: GopherCon LATAM 2026
event_url: https://gopherconlatam.org/

location: Florianópolis, Brasil
address:
  street: ""
  city: Florianópolis
  region: SC
  postcode: ""
  country: Brasil

summary: "Autenticação e autorização em Go para além do JWT: access tokens, OAuth2, OIDC, boas práticas e um estudo de caso em escala."
abstract: "JWT virou quase sinônimo de segurança de API, mas na prática ele é só uma peça de um quadro bem maior. Nesta talk eu volto ao básico do que significam autenticação e autorização, mostro a diferença entre um access token opaco e um JWT, e como o OAuth2 e o OpenID Connect organizam esse mundo — papéis, grants e endpoints — de forma padronizada. Também comento algumas boas práticas que fui aprendendo no caminho, como o velho conselho de \"don't roll your own authentication\" e o uso de soluções já consolidadas (Keycloak, Ory Hydra, Auth0). Para fechar, compartilho um estudo de caso real: a migração de um monólito para microsserviços de identidade em Go, a arquitetura por trás disso e os números em escala — centenas de milhares de tokens gerados e dezenas de milhões de introspecções e checagens de permissão por dia."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2026-09-03T13:00:00-03:00"
# date_end: "2026-09-03T15:00:00-03:00"
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: "2026-09-08T00:00:00-03:00"

authors: [Yan Uehara de Moraes]
tags: [go, gophercon]

# Is this a featured talk? (true/false)
featured: false

image:
  caption: ""
  focal_point: Right

links: []
url_code: "https://github.com/yanuehara-mb/gophercon-2026"
url_pdf: "/talk/autenticacao-e-autorizacao-em-go-alem-do-jwt/auth-go-alem-do-jwt.pdf"
url_slides: ""
url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
