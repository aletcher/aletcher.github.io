---
layout: page
permalink: /code/
title: code
description: Research code releases.
nav: true
---

<h3 class="code">{{"Global Convergence in Differentiable Games"}}</h3>

Here is a [notebook](https://github.com/aletcher/impossibility-global-convergence) to accompany my recent paper, [On the Impossibility of Global Convergence in Multi-Loss Optimization](https://openreview.net/pdf?id=NQbnPjPYaG6). Implements a number of multi-loss optimization methods that are shown to enter limit cycles instead of converging in a two-parameter zero-sum game, despite being weakly-coercive, analytic and nondegenerate. This includes GD, AGD, EG, OMD, CO, SGA, LA, LOLA, SOS, and CGD.

This undesirable phenomenom is shown to apply more generally to any 'reasonable' algorithm in the paper, ruling out the possibility of global convergence guarantees in multi-loss optimization.<br/><br/>


<h3 class="code">{{"Learning in Differentiable Games"}}</h3>

Over the last few years, different communities (multi-agent, optimization & control) have worked on learning in differentiable games. I released a [notebook](https://github.com/aletcher/stable-opponent-shaping) implementing Stable Opponent Shaping ([SOS](https://openreview.net/pdf?id=SyGjjsC5tQ)) along with other popular optimization methods (LOLA, LA, SGA, CO, EG, CGD, LSS). A number of games including matching pennies and the iterated prisoner’s dilemma are included, but feel free to define any n-player game and compare the algorithms yourself.
