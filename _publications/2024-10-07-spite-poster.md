---
title: "SPITE: Simple Polyhedral Intersection Techniques for modified Environments"
collection: publications
category: posters
permalink: /publication/2024-10-07-spite-poster
excerpt: 'Introduces a simple technique for maintaining dynamic roadmaps in changing environments to significantly reduce planning time.'
date: 2024-10-07
venue: '40th Anniversary of the IEEE International Conference on Robotics and Automation'
paperurl: 'https://martasm2.github.io/files/SPITE_poster.pdf'
# citation: 'S Ashur, M Markowicz, M Lusardi, J Motes, M Morales, S Har-Peled, NM Amato, “SPITE: Simple Polyhedral Intersection Techniques for modified Environments,” <i>16th International Workshop on the Algorithmic Foundations of Robotics</i> , Chicago, IL, USA, October 2024.'
---

Motion planning in modified environments is a challenging task, as it compounds the innate difficulty of the motion planning problem with a changing environment. This renders some algorithmic methods such as probabilistic roadmaps less viable, as nodes and edges may become invalid as a result of these changes. In this paper, we present a method of transforming any configuration space graph, such as a roadmap, to a dynamic data structure capable of updating the validity of its nodes and edges in response to discrete changes in obstacle positions. We use methods from computational geometry to compute 3D swept volume approximations of configuration space points and curves to achieve 10-40 percent faster updates and up to 60 percent faster motion planning queries than previous algorithms while requiring a significantly shorter pre-processing phase, requiring minutes instead of hours needed by the competing method to achieve somewhat similar update times.
