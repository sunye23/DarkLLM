# DarkLLM

<a href="https://arxiv.org/abs/2605.18868"><img src="https://img.shields.io/badge/arXiv-2605.18868-b31b1b.svg" alt="arXiv"></a>

Code for the DarkLLM: Learning Language-Driven Adversarial Attacks with Large Language Models

## Opensource plan
- [ ] Release evaluation code.
- [ ] Release model weights.
- [ ] Release training code.

## Contents 
- [Introduction](#introduction)
- [Installation](#installation)
- [Model Weights](#model-weights)
- [Training Data](#training-data-preparation)
- [Training](#training)
- [Evaluation](#evaluation--benchmark)
- [Acknowledgments](#acknowledgments)

## Installation
<details open>
<summary>Installation</summary>

1. Please install the python and pytorch first:
```bash
conda create -n darkllm python=3.10
conda activate darkllm
conda install pytorch==2.3.1 torchvision==0.18.1 pytorch-cuda=12.1 -c pytorch -c nvidia
```

2. Install mmcv:
```bash
pip install mmcv==2.2.0 -f https://download.openmmlab.com/mmcv/dist/cu121/torch2.3/index.html
```

3. Install other dependencies:
```bash
pip install -r requirements.txt
pip install git+https://github.com/facebookresearch/segment-anything.git
pip install open_clip_torch
pip install flash_attn-2.7.3+cu121torch2.3-cp310-cp310-linux_x86_64.whl 
```
</details>
The compiled flash_attn wheel file can be downloaded from this [website](https://github.com/mjun0812/flash-attention-prebuild-wheels/releases).

## Model Weights

## Training Data

## Training

## Evaluation

## Acknowledgments
