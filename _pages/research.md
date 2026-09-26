---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My research focuses on efficient motion planning for dynamic environments and multi-robot systems. I develop algorithms and data structures that reduce the cost of collision checking, replanning, and coordination, with an emphasis on practical C++ implementations and experimental evaluation.

## MR-SPITE: Accelerating Multi-Robot Planning
{: .archive__item-title }

A current focus of my research is extending SPITE-style geometric reasoning to multi-robot planning, where checking for conflicts between robot paths can be expensive. MR-SPITE uses hierarchical swept-volume approximations to bound the space occupied by moving robots. Conservative bounds rule out conflicts between separated motion segments, leaving unresolved cases to the underlying collision checker. This accelerates conflict scans while preserving the behavior of the underlying discretized checking process.

[Paper](https://arxiv.org/abs/2609.23928)

## SPITE: Dynamic Roadmaps for Changing Environments
{: .archive__item-title }

When obstacles move, revalidating a motion-planning roadmap can require many expensive collision checks. SPITE uses precomputed swept-volume approximations and geometric intersection queries to identify roadmap nodes and edges that may be affected by environmental changes. My work has included developing and extending this dynamic-roadmap framework for efficient replanning, connecting algorithm design, geometric reasoning, and C++ implementation.

![SPITE dynamic-roadmap illustration]({{ '/images/spite_fig1.png' | relative_url }})

[Paper](https://arxiv.org/abs/2407.00259) · [Code](https://github.com/parasollab/open-spite) · [Project](https://parasollab.web.illinois.edu/research/spite/)

## Task-and-Motion Planning
{: .archive__item-title }

Task-and-motion planning can repeatedly require geometric validation as a planner considers different object rearrangements. I explored using SPITE-based dynamic roadmaps in a semi-lazy rearrangement solver to estimate motion feasibility during task planning. These estimates guide the search toward promising actions while deferring full motion validation, reducing unnecessary collision checking.

[Paper](https://construction-robots.github.io/papers/110.pdf)

## Vectorized Collision Detection
{: .archive__item-title }

Collision and edge validation can dominate planning runtime, making the organization of geometric computations an important systems problem. In Serialized Red-Green-Gray, we use conservative geometric approximations to classify roadmap edges as valid, invalid, or uncertain. Batch serialization and vectorization enable GPU acceleration of this heuristic validation, complementing the reduction in edges that need full collision checking.

[Paper](https://arxiv.org/abs/2603.28674)

## Space-Time Planning
{: .archive__item-title }

My earlier research explored sampling-based planning in space-time using temporal safe intervals to reason about when motions are feasible around moving obstacles. This work considers future obstacle motion, including uncertain or unknown motion, rather than treating the environment as static at each timestep.

See my [publications]({{ '/publications/' | relative_url }}) for the related papers.
