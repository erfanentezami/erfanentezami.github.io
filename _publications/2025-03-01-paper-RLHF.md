---
title: "LLM Misalignment via Adversarial RLHF Platforms"
collection: publications
category: conferences
permalink: /publication/2024-02-17-paper-title-number-4
excerpt: 'This paper is about fixing template issue #693.'
date: 2024-03-04
venue: 'Preprint - 2025'
paperurl: 'https://arxiv.org/pdf/2503.03039'
citation: #'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

Reinforcement learning has shown remarkable performance in aligning language models with human preferences, leading to the rise of attention towards developing RLHF platforms. These platforms enable users to fine-tune models without requiring any expertise in developing complex machine learning algorithms. While these platforms offer
useful features such as reward modeling and RLHF fine-tuning, their security and reliability remain largely unexplored. Given the growing adoption of RLHF and open-source
RLHF frameworks, we investigate the trustworthiness of these systems and their potential impact on behavior of LLMs. In this paper, we present an attack targeting publicly
available RLHF tools. In our proposed attack, an adversarial RLHF platform corrupts
the LLM alignment process by selectively manipulating data samples in the preference
dataset. In this scenario, when a user’s task aligns with the attacker’s objective, the
platform manipulates a subset of the preference dataset that contains samples related
to the attacker’s target. This manipulation results in a corrupted reward model, which
ultimately leads to the misalignment of the language model. Our results demonstrate
that such an attack can effectively steer LLMs toward undesirable behaviors within the
targeted domains. Our work highlights the critical need to explore the vulnerabilities of
RLHF platforms and their potential to cause misalignment in LLMs during the RLHF
fine-tuning process.
