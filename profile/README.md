# vietfood 🍜

**small software for people who want to understand how things work.**

vietfood is a tiny open-source engineering lab for building things that are usually hidden behind large frameworks. complicated systems become much less mysterious when you build a small one yourself.

we work around ML systems, developer tools, inference, compilers, GPU programming, and learning material. the projects are intentionally small enough to read, modify, break, and rebuild. some are serious engineering exercises, some are experiments, and some are just things that sounded fun after work.

## what we're cooking

🍜 [pho-code](https://github.com/vietfood/pho-code): **a coding agent in a window you own.**

a small desktop coding agent built around [Pi](https://github.com/earendil-works/pi). `pho-code` builds the product around it — the UI, tools, skills, prompts, permissions, and workflow.

this one is built heavily with AI. the interesting experiment is the product itself: how far can you push a coding-agent workspace when the whole thing is source you can change?

fork it, change the prompt, replace the tools, rebuild the UI. make it yours.

🍚 [comtam](https://github.com/vietfood/comtam): **a tiny deep-learning framework for Apple Silicon.**

`comtam` is an eager-mode tensor framework in C++20 built to understand the machinery underneath frameworks like `PyTorch`: storage, tensors, views, strides, broadcasting, kernels, autograd, and eventually neural networks.

> an eager-mode tensor framework in 2026, bro you're outdated lol.

the code is written by a human, with AI acting mostly as a teacher, reviewer, and debugger. the point is not to replace `PyTorch` or `MLX` (love them). the point is to understand enough of the stack that it stops looking like magic.

🥞 [banhxeo](https://github.com/vietfood/banhxeo): **a tiny LLM inference engine in the making.**

`banhxeo` started as another tiny tensor framework, focused more on lazy graphs, compilation, and Triton code generation. that eventually overlapped too much with `comtam`, so the project is moving lower in the stack.

the new goal is a small inference engine for exploring graph execution, compilation, kernel generation, memory planning, scheduling, model loading, and the rest of the machinery required to actually run neural networks.

🥖 [bami-hub](https://github.com/vietfood/bami-hub): **an open learning kitchen for ML, systems, and AI.**

`bami-hub` is the learning side of `vietfood`. it contains original material together with translated or adapted open-source books, courses, notes, and other educational resources.

ideally the learning material and the software meet somewhere in the middle: read the idea, inspect the implementation, break something, then build your own version.

## philosophy

### build to understand

we like tiny implementations because you can hold them in your head.

production systems need abstractions, compatibility layers, optimizations, and years of accumulated engineering decisions. those things are necessary, but they are terrible places to start learning. we would rather feel the problem first and introduce the abstraction after we understand why it needs to exist.

### use AI, don't hide it

different projects here use AI differently. sometimes the human writes and the AI teaches. sometimes the AI writes and the human directs. sometimes both produce terrible code and spend the next evening figuring out why. 

> the interesting question is not who typed every line. it is whether the system is understood well enough to modify, debug, and own.

### learn in public

things here will fail, get rewritten, and occasionally turn into completely different projects. that's fine. a repository is allowed to show the path between "I wonder how this works" and "okay, now I actually understand it."

---

**build things. break things. understand why.**
