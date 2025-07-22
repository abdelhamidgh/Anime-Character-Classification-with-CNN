# Anime-Character-Classification-with-CNN


This project demonstrates a Convolutional Neural Network (CNN) for classifying anime character faces using a subset of the [AniWho dataset](https://arxiv.org/abs/2203.14953).

The AniWho dataset consists of over 9,700 images across 130 anime characters. For this tutorial, we simplify the problem by using two character classes: **Anastasia** and **Takao**, each with 50 images sourced from Danbooru.

##  Dataset Overview

- Source: Danbooru via the AniWho paper
- Classes: 2 (Anastasia, Takao)
- Images per class: 50
- Format: `.jpg` in two subdirectories

##  Objective

- Use a CNN to classify between two anime characters.
- Apply PyTorch for data loading, training, and evaluation.
- Visualize training progress and performance.

##  Setup

```bash
pip install torch torchvision matplotlib numpy pillow
