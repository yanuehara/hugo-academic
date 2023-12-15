---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Gerenciamento e proteção do serviço de autenticação adaptativa social para
  ambientes IoT contra ataques de difamação
subtitle: ''
summary: ''
authors:
- Yan Uehara de Moraes
tags: []
categories: []
date: '2022-05-01'
lastmod: 2023-10-14T14:09:29-03:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: [galena]
publishDate: '2023-10-14T17:13:15.103177Z'
publication_types:
- '7'
abstract: "The IoT devices usually have limited computational, energetic and communication capabilities, and also they have to deal with challenges related to security and communication reliability. The IoT network employs authentication in order to maintain its security and the diversity of authentication mechanisms derived from the heterogeneity of the network has led to emergence of adaptive authentication systems. These systems resort to input factors in order to determine autonomously the suitable mechanism for a specific situation. However, current adaptive authentication approaches are not suitable for ad hoc networks, since they restrict themselves in using one input factor, such as context, and do not take into account other factors of the devices it interacts. In addition, they employ techniques that are not suitable to the devices processing restrictions. This dissertation investigated the benefits come from social perception, derived from the Social Internet of Things paradigm (SIoT), as adaptation factor in order to exchange services among IoT devices according to context compatibility. Thus, it is presented the GALENA system (manaGement of Adaptive authentication based on poLiciEs aNd sociAl trust), which decides the suitable authentication mechanism to apply in authentication procedures in IoT devices. The system address the devices' computational restrictions employing policies that dictates the need for adaptation. Moreover, in order to prevent malicious behaviour aimed at the social recommendations exchanged, such as the badmouthing attack that seeks to diminish the trust over a device, GALENA employs Data Provenance techniques to authenticate the source of the recommendation. Thus, it is able to discard manipulated recommendations that aim to defame other devices. GALENA was evaluated through simulations in NS-3 and the results demonstrate its efficiency in adapting and selecting the suitable authentication mechanism each interaction. The system achieved a compatibility rate of 97% in an IoT network with 200 devices and 98% in one with 400 devices, with trust accuracy of 64% in both configurations. It also achieved a detection rate of the badmouthing attack up to 90.62% with 200 devices and up to 74.76% with 400 devices, with an detection accuracy of 91% and of 79% respectively. Further, the system reached a low false negative rate, around 10% with 200 devices and 31% with 400 devices."
publication: ''
links:
- name: URL
  url: https://acervodigital.ufpr.br/handle/1884/77460
---
