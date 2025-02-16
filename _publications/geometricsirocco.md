---
title: "Distributed interactive proofs for the recognition of some geometric intersection graph classes"
collection: publications
category: conferences
permalink: /publication/geometricsirocco
date: 2022-02-01
venue: 'SIROCCO'
paperurl: 'http://academicpages.github.io/files/geometricsirocco.pdf'
---

A graph $G = (V, E)$ is a geometric intersection graph if every node $v \in V$ is identified
with a geometric object of some particular type, and two nodes are adjacent if the corresponding
objects intersect. Geometric intersection graph classes have been studied from both the theoretical
and practical point of view. On the one hand, many hard problems can be eﬃciently solved or
approximated when the input graph is restricted to a geometric intersection class of graphs. On the
other hand, these graphs appear naturally in many applications such as sensor networks, scheduling
problems, and others. Recently, in the context of distributed certification and distributed interactive
proofs, the recognition of graph classes has started to be intensively studied. Diﬀerent results related
to the recognition of trees, bipartite graphs, bounded diameter graphs, triangle-free graphs, planar
graphs, bounded genus graphs, H-minor free graphs, etc., have been obtained.
The goal of the present work is to design eﬃcient distributed protocols for the recognition of relevant
geometric intersection graph classes, namely permutation graphs, trapezoid graphs, circle graphs
and polygon-circle graphs. More precisely, for the two first classes we give proof labeling schemes
recognizing them with logarithmic-sized certificates. For the other two classes, we give three-round
distributed interactive protocols that use messages and certificates of size $O(\log n)$. Finally, we
provide logarithmic lower-bounds on the size of the certificates on the proof labeling schemes for
the recognition of any of the aforementioned geometric intersection graph classes.