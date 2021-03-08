---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "GALENA"
summary: This project proposes a system for adaptive authentication management, supported by social trust and policies. The GALENA system (manaGement of Adaptive authentication based on poLiciEs aNd sociAl trust), seeks to determine the most appropriate authentication profile to perform authentication between devices based on the devices' social trust
authors: [Yan Uehara de Moraes, Carlos Pedroso, Michele Nogueira, Aldri Santos]
tags: [IoT, Adaptive Authentication, Social Trust, Policies]
categories: []
date: 2021-03-07T12:52:27-03:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  placement: 0
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

url_code: ""
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

As the devices become present in different social and human settings they come in contact with sensitive information. In those situations, they need to verify other device's identities to interact with them.
However, as multiple authentication mechanisms for IoT exists, systems capable to change the authentication mechanism in use becomes necessary. Adaptive authentication systems allow devices to react to modification in input factors and use a mechanism suitable to the situation they encounter. However, existing approaches do not consider the social relation that exists among devices as an adaptation factor. This project proposes a system for adaptive authentication management, supported by social trust and policies. The system, called **GALENA** (mana**G**ement of **A**daptive authentication based on poLici**E**s a**N**d soci**A**l trust), seeks to determine the most appropriate authentication profile to perform authentication between devices. It uses social trust, calculated from the sociability between devices, as an input to the adaptation system. In addition to social trust, the system uses policies to help choose the appropriate authentication mechanism. Those techniques allows flexibility in the device authentication process and provides robustness in service relations.