---
title: 
layout: default
featured: true
---
Hi! I'm currently a PhD student in my last year at MIT advised by [Jonathan Ragan-Kelley](https://people.csail.mit.edu/jrk/). Before joining MIT I received a masters in Computer Science at Carnegie Mellon and a B.A. in Economics at Dartmouth College. I've interned at FAIR and Adobe Research during my PhD and had the pleasure of collaborating with and learning from many people including [Andrew Adams](https://andrew.adams.pub/), [Fredo Durand](https://people.csail.mit.edu/fredo/), [Michaël Gharbi](https://mgharbi.com/), [Shoaib Kamil](https://research.adobe.com/person/shoaib-kamil/), and [Tzu-Mao Li](https://cseweb.ucsd.edu/~tzli/).

## Research Interests
My goal is to create program synthesis environments that give users flexible control over design and implementation, from the novice who wants full automation, to the expert who wants surgical synthesis, preserving low-level control over sensitive sub-tasks. My work connects methods from domain-specific programming, high performance computing, program synthesis, and machine learning to build systems for automatic program generation. 

In the past I've worked on [finding fast approximations for large image and audio filters](karimama.com/papers) and [program synthesis for demosaicking](https://dl.acm.org/doi/full/10.1145/3508461), where the user wants to maximize both program throughput and output quality. These competing objectives often exist in spaces where there are intractably many valid program mutations with non-obvious and entangled effects to consider, making it impossible to adequately explore program designs without automated search tools.

I've also considered cases where there is only one objective, like maximizing throughput, in the context of [automatically generating schedules for Halide programs](https://dl.acm.org/doi/10.1145/3306346.3322967). Even here, the space of optimization decisions is highly complex and difficult to navigate. Before our autoscheduler, only experts could find good schedules within a reasonable amount of time, relying on heuristics acquired through years of experience. 

I'm currently studying time-saving exploration tools and linters for performance optimiztion in user-schedulable languages, with the goals of transparent workflow augmentation for the expert and domain knowledge transfer for the novice. 



