---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "GopherCon Brazil 2024"
subtitle: ""
summary: "The Brazilian edition of GopherCon happened in May 2024 in Florianopolis. Check out my experience in attending the conference and my highlights of the talks"
authors: [Yan Uehara de Moraes]
tags: [go, golang, gophercon]
categories: [conference]
date: 2024-08-25T21:46:00-03:00
lastmod: 2024-08-25T21:46:00-03:00
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

Hello all! I want to start the first post of this blog with my personal experience in GopherCon Brasil 2024, a tech conference about the Go programming language in its Brazilian version.  I’ve been programming using the Go language for over two and a half years now and I continuously try to learn about the new features of the language. My first contact with the language was developing new features in a preexisting project. But lately our team have been using Go to in a high throughput setting as part of out IAM system.

I learned about the Brazilian edition of the conference in late 2023 due to a talk given by our Architect. At that year's conference he gave a talk about SAGA implementation in our company using Go [[PDF](https://gopherconbr.org/talks/2023/saga_pattern.pdf)/[Presentation](https://www.youtube.com/watch?v=3CwaDFF-LbM&ab_channel=GopherConBrasil), in Portguese]. After the conference was over, he shared it with the company's developers, encouraging us to contribute to future editions. Given our ongoing work with Go to build microservices supporting the IAM system within our company, we decided to submit a case-study-style talk showcasing our architecture and performance achievements. Although our submission was not selected for this edition, we remain committed and plan to revise it and resubmit for the 2025 edition.

### The Conference

The conference took place in the beautiful city of Florianopolis at the beginning of May 2024. This year, there were many technical, hands-on talks showcasing the language's features to both beginners and advanced users.

Day 1: The first day began with a panel discussing the language, carreer and its future. The day was packed with talks about go’s gorutines, CLIs, the `slog` library, go in embedded devices, just to name a few.

Day 2: On the second day we had talks about search engines in Go, concurrency patterns in Go, cryptography and encryption/decription using Go, application scaffolding using the ‘embed’  package, Go running in the browser via web assembly. Finally the conference and the day ended with a keynote about Hexagonal, Clean-Arch and DDD.

#### Key Takeaways:
Four talks stood out to me:

1. **Getting to know the “log/slog”: The Go’s standard library of logging** (free translation fom portuguese: Conhecendo a "log/slog": A biblioteca de log da Standard Library do Go): This talk introduced the new `slog` module in the standard library in go [[PDF](https://docs.google.com/presentation/d/10dhEs1yagXbOX35dmxbZ4igrfUBXz6e25BkcnPXHupg/edit#slide=id.g1f20d11cc68_0_1105)/[Presentation](https://www.youtube.com/watch?v=xszQjCqLX6w&ab_channel=GopherConBrasil), in Portuguese]. It was particularly interesting as we had emulated some of the implementation, such as default data for each log, in some microservices in our company to facilitate observability.
2. **Profile-Guided Optimization:** This session showcased how we can build a version of our app tailored to the work it performs under load [[PDF](https://docs.google.com/presentation/d/1uCK7PgXT0iUg-WSsLXlxxMKr5p_-xA2_6KH5dogEygg/edit#slide=id.g1f20d11cc68_0_1102)/[Presentation](https://www.youtube.com/watch?v=V2LSnbvylz4&ab_channel=GopherConBrasil), in Portuguese] and how the optimization can lead to performance improvement. It also showed how to use the integrated profilling tools to analyze the application and identify bottlenecks.
3. **Go in Embedded Devices:** Two talks showcases the use of Go in embedded devices “GoIoT: Innovating in connectivity using Go and Smart Devices” (from the Portuguese “GoIoT: Inovando na Conectividade com Go e Dispositivos Inteligentes”) [[PDF](https://docs.google.com/presentation/d/1-8ueQOlb4ZeEl7KfhQe2AK8_69upghFQw2n_MvCjgnU/edit#slide=id.g1f20d11cc68_0_1102)/[Presentation](https://www.youtube.com/watch?v=ICqv5jJYLEA&ab_channel=GopherConBrasil), in Portuguese] and “An Experience Developing for Embedded Systems Using Go” (from the portuguese “Uma Experiência de Desenvolvimento de Software Embarcado Usando Go”) [[PDF](https://gopherconbr.org/talks/2024/SistemasEmbarcados.pdf)/[Presentation](https://www.youtube.com/watch?v=FSK-i0goCGs&ab_channel=GopherConBrasil), in Portuguese]. The first taks introduced the use of go for microcontrolers and microprocessors, including how to dowsize the application to fit in those platforms using runtimes such as TinyGo. The second talks showcased how the authors migrated to using a Raspberry Pi in their proof-of-concept product to an integrated microcontroler without changing their app and just recompiling to the microcontorler’s platform as compilation target. Both these talks were very interesting to me as they closely relate to my master’s thesis proposal, and I could envision using Go to make a proof-of-concept of my proposed system for embedded systems.

### Closing thoughts
GopherCon Brasil 2024 exceeded all my expectations in terms of the depth of the features showcased. From the mentioned talks, I’m looking forward to incorporate the usage of the `slog` module in our standardization effort of logging in our microservices . And, as for the conference, I hope to have our IAM talk accepted in the 2025 edition.

Have you attended any tech conference? Have you attended The GopherCon Brasil 2024? Please share your opinions and thoughts in the comments.