---
layout: post
title:  "Minesweeper Solving Program"
date:   2021-08-09
excerpt: "CS440 Intro Artificial Intelligence"
project: true
tag:
- csp
- ai
comments: false
---
This was the project from CS440 Intro Artificial Intelligence. The goal was to create a bot that can play minesweeper.

## Basic Agent
* The basic agent cannot infer. It only plays the safest moves possible
* If no hidden cell can be identified as a mine or safe, it randomly pick a cell to reveal

## Advances Agent
* This bot was implemented based on CSP(Constraint Satisfaction Problem)
* Creating constraints as an equation and adding, removing, or updating constraints in knowledge
* Infer next step based on this knowledge
* If no hidden cell can be identified as a mine or safe, it randomly pick a cell to reveal

## Bonus Advances Agent
* If no hidden cell can be identified as a mine or safe, it picks a cell to reveal based on probability
* Calculate all the possible scenarios based on the knowledge by using combination and product
* Compute the probability of each cell those in the equations in knowledge(number of cells showing up in the scenario/number of total scenario).

![](../assets/img/mine.png)

<div markdown="0">
    <a href="https://github.com/Norden-Tenzin/440ArtificialIntelligence/tree/master/MINESWEEPER" class="btn">Code</a>
    <a href="https://github.com/Norden-Tenzin/440ArtificialIntelligence/blob/master/MINESWEEPER/Report2_tn266_sk1998.pdf" class="btn">Tech Report</a>
</div>
