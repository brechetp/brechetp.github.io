---
title: "When are solutions connected in deep networks?"
collection: publications
permalink: /files/publications/NBM2021When.pdf
excerpt: 'The question of how and why the phenomenon of mode connectivity occurs
in training deep neural networks has gained remarkable attention in the research
community. From a theoretical perspective, two possible explanations have been
proposed: (i) the loss function has connected sublevel sets, and (ii) the
solutions found by stochastic gradient descent are dropout stable. While these
explanations provide insights into the phenomenon, their assumptions are not
always satisfied in practice. In particular, the first approach requires the
network to have one layer with order of N neurons (N being the number of
training samples), while the second one requires the loss to be almost invariant
after removing half of the neurons at each layer (up to some rescaling of the
remaining ones). In this work, we improve both conditions by exploiting the
quality of the features at every intermediate layer together with a milder
over-parameterization requirement. More specifically, we show that: (i) under
generic assumptions on the features of intermediate layers, it suffices that the
last two hidden layers have order of √N neurons, and (ii) if subsets of features
at each layer are linearly separable, then almost no over-parameterization is
needed to show the connectivity. Our experiments confirm that the proposed
condition ensures the connectivity of solutions found by stochastic gradient
descent, even in settings where the previous requirements do not hold.'
date: 2021-12-01
venue: 'NeurIPS 2021'
paperurl: 'https://proceedings.neurips.cc/paper/2021/file/af5baf594e9197b43c9f26f17b205e5b-Paper.pdf'
---
This paper is about the number 1. The number 2 is left for future work.

[Download paper here](http://academicpages.github.io/files/paper1.pdf)

Recommended citation: Your Name, You. (2009). "Paper Title Number 1." <i>Journal 1</i>. 1(1).
