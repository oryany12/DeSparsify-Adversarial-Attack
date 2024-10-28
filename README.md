# DeSparsify: Adversarial Attack Against Token Sparsification Mechanisms
[![Published at NeurIPS 2024](https://img.shields.io/badge/Published-NeurIPS%202024-blue.svg)](link_to_paper)

## Abstract
Vision transformers have contributed greatly to advancements in the computer vision domain, demonstrating state-of-the-art performance in diverse tasks (\eg, image classification, object detection).
However, their high computational requirements grow quadratically with the number of tokens used.
\emph{Token sparsification} techniques have been proposed to address this issue.
These techniques employ an input-dependent strategy, in which uninformative tokens are discarded from the computation pipeline, improving the model's efficiency.
However, their dynamism and average-case assumption makes them vulnerable to a new threat vector -- carefully crafted adversarial examples capable of fooling the sparsification mechanism, resulting in worst-case performance.
In this paper, we present \emph{DeSparsify}, an attack targeting the availability of vision transformers that use token sparsification mechanisms.
The attack aims to exhaust the operating system's resources, while maintaining its stealthiness.
Our evaluation demonstrates the attack's effectiveness on three token sparsification techniques and examines the attack's transferability between them and its effect on the GPU resources.
To mitigate the impact of the attack, we propose various countermeasures.