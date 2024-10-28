# DeSparsify: Adversarial Attack Against Token Sparsification Mechanisms
[![Published at NeurIPS 2024](https://img.shields.io/badge/Published-NeurIPS%202024-blue.svg)](link_to_paper)

## Abstract
Vision transformers have contributed greatly to advancements in the computer vision domain, demonstrating state-of-the-art performance in diverse tasks (eg. image classification, object detection).
However, their high computational requirements grow quadratically with the number of tokens used.
*Token sparsification* techniques have been proposed to address this issue.
These techniques employ an input-dependent strategy, in which uninformative tokens are discarded from the computation pipeline, improving the model's efficiency.
However, their dynamism and average-case assumption makes them vulnerable to a new threat vector - carefully crafted adversarial examples capable of fooling the sparsification mechanism, resulting in worst-case performance.
In this paper, we present *DeSparsify*, an attack targeting the availability of vision transformers that use token sparsification mechanisms.
The attack aims to exhaust the operating system's resources, while maintaining its stealthiness.
Our evaluation demonstrates the attack's effectiveness on three token sparsification techniques and examines the attack's transferability between them and its effect on the GPU resources.
To mitigate the impact of the attack, we propose various countermeasures.

### Table of Contents
- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Metrics and Evaluation](#metrics-and-evaluation)
- [Contributing](#contributing)
- [Citation](#citation)

## Overview
This repository contains the implementation and results of "DeSparsify," an adversarial attack designed to expose vulnerabilities in vision transformers using token sparsification techniques. We provide code, data, and detailed instructions for reproducing our experiments as presented at NeurIPS 2024.

## Installation

## Usage

## Results

## Metrics and Evaluation

## Contributing

## Citation
```bibtex
@article{yehezkel2024desparsify,
  title={DeSparsify: Adversarial Attack Against Token Sparsification Mechanisms in Vision Transformers},
  author={Yehezkel, Oryan and Zolfi, Alon and Baras, Amit and Elovici, Yuval and Shabtai, Asaf},
  journal={arXiv preprint arXiv:2402.02554},
  year={2024}
}
```
