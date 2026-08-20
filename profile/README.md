# vietfood 🍜

**Small open-source software for understanding how modern AI systems work.**

Vietfood is an independent open-source engineering organization focused on AI systems, developer tools, GPU computing, inference, and technical education.

We build small, understandable implementations of systems that are usually hidden behind much larger frameworks. The goal is to make the underlying ideas easier to study, modify, and experiment with - from tensor runtimes and LLM execution to coding agents and learning resources.

Our projects are primarily experimental and educational. Some are written manually as engineering exercises, while others make extensive use of AI-assisted development. In both cases, we care about understanding the system, documenting the design, and keeping the implementation accessible.

## Projects

| Project                                                 | Stars                                                                                                                                  | What it is                                       | Details                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| ------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 🍜 **[Pho Code](https://github.com/vietfood/pho-code)** | [![GitHub stars](https://img.shields.io/github/stars/vietfood/pho-code?style=social)](https://github.com/vietfood/pho-code/stargazers) | A coding agent in a window you own               | An open-source desktop coding agent built around [Pi](https://github.com/earendil-works/pi).                                                                              |
| 🍚 **[comtam](https://github.com/vietfood/comtam)**     | [![GitHub stars](https://img.shields.io/github/stars/vietfood/comtam?style=social)](https://github.com/vietfood/comtam/stargazers)     | A tiny deep-learning framework for Apple Silicon | An eager-mode tensor framework written in C++20 and Metal, designed as both a working framework and a self-study project.                                                                                                      |
| 🥞 **[banhxeo](https://github.com/vietfood/banhxeo)**   | [![GitHub stars](https://img.shields.io/github/stars/vietfood/banhxeo?style=social)](https://github.com/vietfood/banhxeo/stargazers)   | A small LLM inference engine                     | Originally a lazy tensor framework exploring computation graphs and Triton code generation, banhxeo is now evolving into a dedicated LLM inference engine. |
| 🥖 **[bami-hub](https://github.com/vietfood/bami-hub)** | [![GitHub stars](https://img.shields.io/github/stars/vietfood/bami-hub?style=social)](https://github.com/vietfood/bami-hub/stargazers) | Open learning material for AI, ML, and systems   | A learning hub for original courses and notes together with carefully adapted or translated open-source educational material. The goal is providing free knowledge for Vietnamese community.                                                                                                                                                                                                                             |

## Philosophy

| Principle                                  | What we mean                                                                                                                                                                                                                                                                                                                 |
| ------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 🔨 **Build to understand**                 | Large production systems accumulate abstractions, compatibility requirements, optimizations, and historical constraints. We prefer starting with implementations small enough to understand end to end, then adding complexity when the problem actually requires it.                                                        |
| 🔍 **Keep the machinery visible**          | Abstractions are useful, but they should not make the underlying system impossible to inspect. We value explicit designs, readable implementations, and code that can be modified without first understanding millions of lines around it.                                                                                   |
| 🧪 **Learn in public**                     | These repositories are also records of the learning process. Designs change, implementations are rewritten, experiments fail, and projects sometimes move in entirely different directions as our understanding improves.                                                                                                    |
| 🤖 **Use AI openly**                       | AI is used differently across Vietfood. Some projects are intentionally implemented by hand, with AI acting as a teacher, reviewer, and debugger. Others use AI heavily for implementation while the human focuses on architecture, testing, direction, and product design. We prefer being explicit about that distinction. |
| 📖 **Source is part of the documentation** | Documentation and courses can explain an idea, but the implementation should eventually be understandable too. A project succeeds educationally when someone can read it, modify it, break it, and understand why it works.                                                                                                  |

## About

Vietfood is named after Vietnamese food, and most projects follow the same convention.

We build these projects because understanding a system deeply enough to recreate a small version of it is one of the best ways we know to learn.

**Build things. Break things. Understand why.**
