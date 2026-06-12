---
layout: page
permalink: /repositories/
title: code
description: Open-source software released as part of my research.
nav: true
nav_order: 4
---

## ProMis — Probabilistic Mission Design

ProMis is a framework enabling agents to formalize knowledge about local rules and traffic regulations to constrain their actions and movements under uncertainty. It employs **probabilistic first-order logic** to combine formal symbolic reasoning with probabilistic inference, generating probability fields across state spaces that indicate how likely an agent is to satisfy its constitutional guidelines. These fields support path planning, automated clearance decisions, parameter optimization, and mission impact analysis.

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% include repository/repo.liquid repository="HRI-EU/ProMis" %}
</div>

---

## Resin — Reactive Signal Inference

Resin is a **probabilistic first-order logic programming language** for building reactive inference pipelines over continuous, asynchronous data streams. The core library is written in Rust with a Python package available on PyPI. It compiles programs through Answer Set Programming into reactive computation graphs that perform algebraic model counting in real time.

Resin supports multiple inference modes including probabilistic inference, most-probable explanations, fuzzy degree-of-truth evaluation, and forward-mode automatic differentiation for gradient-based parameter learning.

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% include repository/repo.liquid repository="simon-kohaut/Resin" %}
</div>

---

## CycliST — Cyclical State Transition Benchmark

CycliST is a dataset generation framework and benchmark for evaluating **video-language models on cyclical state transition reasoning**, motivated by traffic scenarios such as traffic lights, roundabouts, and pedestrian crossings. Randomized scenes are rendered with Blender and automatically labeled to produce video question-answer pairs. Accepted at *Data-centric Machine Learning Research (DMLR)*.

The dataset itself available on [HuggingFace](https://huggingface.co/datasets/AIML-TUDA/CycliST).

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% include repository/repo.liquid repository="simon-kohaut/CycliST" %}
</div>
