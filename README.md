# Bootstrapping Multi-Armed Bandits
[Imad AOUALI](https://www.linkedin.com/in/imad-aouali/)

## Abstract

Multi-Armed bandits have attracted a lot of attention in various applications, from recommender systems and information retrieval to healthcare and finance, due to their performance, their simplicity and properties such as learning from partial feed back. Bootstrapping is a powerful, computer-based method for statistical inference. It is a resampling method which samples independently with replacement from an existing sample data with same sample size n, and performing inference among these resampled data. Two recent papers proposed Bootstrap-based approaches for multi-armed bandit problems. This project aims to provide a comprehensive review of the use of Bootstrapping in multi-armed bandit problems by contrasting those approaches and discussing their benefits compared to traditional bandit approaches like UCB, kl-UCB, and Thompson Sampling.

***
## Repository Structure
***

This repository consists in two directories with specific purposes:

- `documents`: This directory contains 2 papers proposing the use of bootstrapping techniques for Bandit problems.
  1. `Bootstrapping Upper Confidence Bound`
  2. `Giro Bootstrapping Exploration in Multi-Armed Bandits`
- `codes`: images on which we apply high resolution algorithms.
  1. `Arms.py`: Different classes of arms, all of them have a sample() method which produce rewards.
  2. `BanditBaselines.py`: Two bandit baselines.
  3. `BanditTools.py`: Useful functions for bandit algorithms.
  4. `StochasticBandit.py`: Useful functions that create specific types of MAB.
  5. `StochasticBandit.py`: Useful functions that create specific types of MAB.
  
---

For any information, feedback or questions, please [contact us][imad-email]

---
[anas-email]: mailto:essounaini97@gmail.com
[ali-email]: mailto:mourtada.ali1997@gmail.com 
[imad-email]: mailto:imadaouali9@gmail.com 
