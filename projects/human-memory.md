---
layout: page
title: A Machine With Human-Like Memory Systems
subtitle: A machine with a symbolic memory system (knowledge graph) trained with reinforcement learning.
cover-img: /assets/img/projects/human-memory.png
thumbnail-img: /assets/img/projects/human-memory.png
tags:
  [
    reinforcement learning,
    AI,
    human memory,
    knowledge graph,
    machine learning,
    deep learning,
  ]
author: Taewoon Kim
comments: true
---

# [A Machine With Human-Like Memory Systems](https://arxiv.org/abs/2204.01611)

Inspired by the cognitive science theory, we explicitly model an agent with
both semantic and episodic memory systems, and show that it is better than
having just one of the two memory systems. In order to show this, we have
designed and released our own challenging environment, "the Room", compatible
with OpenAI Gym, where an agent has to properly learn how to encode, store,
and retrieve memories to maximize its rewards. The Room environment allows for
a hybrid intelligence setup where machines and humans can collaborate. We show
that two agents collaborating with each other results in better performance
than one agent acting alone. We have open-sourced our code and models at [https://github.com/tae898/explicit-memory](https://github.com/tae898/explicit-memory).

# [A Machine with Short-Term, Episodic, and Semantic Memory Systems](https://arxiv.org/abs/2212.02098)

<!-- padding-bottom: 56.25% is for 16:9. For an aspect ratio of 1:1 change to this value to 100% */  -->
<div style="position: relative; padding-bottom: 56.25%">
  <iframe
    style="width: 100%; height: 100%; position: absolute; left: 0px; top: 0px"
    frameborder="0"
    width="100%"
    height="100%"
    allowfullscreen
    allow="autoplay"
    src="
  https://www.youtube.com/embed/MsoyjiYuHF0
 "
  >
  </iframe>
</div>

Inspired by the cognitive science theory of the explicit human memory systems,
we have modeled an agent with short-term, episodic, and semantic memory
systems, each of which is modeled with a knowledge graph. To evaluate this
system and analyze the behavior of this agent, we designed and released our
own reinforcement learning agent environment, "the Room", where an agent has
to learn how to encode, store, and retrieve memories to maximize its return by
answering questions. We show that our deep Q-learning based agent successfully
learns whether a short-term memory should be forgotten, or rather be stored in
the episodic or semantic memory systems. Our experiments indicate that an
agent with human-like memory systems can outperform an agent without this
memory structure in the environment. The environment is open-sourced at [https://github.com/tae898/room-env](https://github.com/tae898/room-env), and the agent is open-sourced at [https://github.com/tae898/explicit-memory](https://github.com/tae898/explicit-memory).
