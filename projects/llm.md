---
layout: page
title: Large Language Models
subtitle: It's all about predicting the next word given the history of words.
cover-img: /assets/img/projects/llm.png
thumbnail-img: /assets/img/projects/llm.png
tags: [llm, AI, large language model, machine learning, deep learning]
author: Taewoon Kim
comments: true
---

# [Multitask Prompted Training Enables Zero-Shot Task Generalization](https://arxiv.org/abs/2110.08207)

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
    https://www.youtube.com/embed/iJ0IVZgGjTM?si=tDniFfDSDIIiomRa
"
  >
  </iframe>
</div>

Large language models have recently been shown to attain reasonable zero-shot
generalization on a diverse set of tasks (Brown et al., 2020). It has been
hypothesized that this is a consequence of implicit multitask learning in
language models' pretraining (Radford et al., 2019). Can zero-shot
generalization instead be directly induced by explicit multitask learning? To
test this question at scale, we develop a system for easily mapping any
natural language tasks into a human-readable prompted form. We convert a large
set of supervised datasets, each with multiple prompts with diverse wording.
These prompted datasets allow for benchmarking the ability of a model to
perform completely held-out tasks. We fine-tune a pretrained encoder-decoder
model (Raffel et al., 2020; Lester et al., 2021) on this multitask mixture
covering a wide variety of tasks. The model attains strong zero-shot
performance on several standard datasets, often outperforming models up to 16x
its size. Further, our approach attains strong performance on a subset of
tasks from the BIG-bench benchmark, outperforming models up to 6x its size.
All trained models are available at [https://github.com/bigscience-workshop/t-zero](https://github.com/bigscience-workshop/t-zero) and all prompts are available at [https://github.com/bigscience-workshop/promptsource](https://github.com/bigscience-workshop/promptsource).

# [Bloom: A 176b-parameter open-access multilingual language model](https://arxiv.org/abs/2211.05100)

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
    https://www.youtube.com/embed/sKTbV7GZsMA?si=wcq2FWG9HkdxNsYx
"
  >
  </iframe>
</div>

Large language models (LLMs) have been shown to be able to perform new tasks
based on a few demonstrations or natural language instructions. While these
capabilities have led to widespread adoption, most LLMs are developed by
resource-rich organizations and are frequently kept from the public. As a step
towards democratizing this powerful technology, we present BLOOM, a
176B-parameter open-access language model designed and built thanks to a
collaboration of hundreds of researchers. BLOOM is a decoder-only Transformer
language model that was trained on the ROOTS corpus, a dataset comprising
hundreds of sources in 46 natural and 13 programming languages (59 in total).
We find that BLOOM achieves competitive performance on a wide variety of
benchmarks, with stronger results after undergoing multitask prompted
finetuning. To facilitate future research and applications using LLMs, we
publicly release our models and code under the Responsible AI License.

# [Promptsource: An integrated development environment and repository for natural language prompts](https://arxiv.org/abs/2202.01279)

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
    https://www.youtube.com/embed/gIthK9J52IM?si=e2HYB9s0nJHW6anA
"
  >
  </iframe>
</div>

PromptSource is a system for creating, sharing, and using natural language
prompts. Prompts are functions that map an example from a dataset to a natural
language input and target output. Using prompts to train and query language
models is an emerging area in NLP that requires new tools that let users
develop and refine these prompts collaboratively. PromptSource addresses the
emergent challenges in this new setting with (1) a templating language for
defining data-linked prompts, (2) an interface that lets users quickly iterate
on prompt development by observing outputs of their prompts on many examples,
and (3) a community-driven set of guidelines for contributing new prompts to a
common pool. Over 2,000 prompts for roughly 170 datasets are already available
in PromptSource. PromptSource is available at [https://github.com/bigscience-workshop/promptsource](https://github.com/bigscience-workshop/promptsource).

# [EmoBERTa: Speaker-Aware Emotion Recognition in Conversation with RoBERTa](https://arxiv.org/abs/2108.12009)

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
    https://www.youtube.com/embed/qbr7fNd6J28?si=ta_MB3w6xTXZW8oJ
"
  >
  </iframe>
</div>

We present EmoBERTa: Speaker-Aware Emotion Recognition in Conversation with
RoBERTa, a simple yet expressive scheme of solving the ERC (emotion
recognition in conversation) task. By simply prepending speaker names to
utterances and inserting separation tokens between the utterances in a
dialogue, EmoBERTa can learn intra- and inter- speaker states and context to
predict the emotion of a current speaker, in an end-to-end manner. Our
experiments show that we reach a new state of the art on the two popular ERC
datasets using a basic and straight-forward approach. We've open-sourced our
code and models at [https://github.com/tae898/erc](https://github.com/tae898/erc).
