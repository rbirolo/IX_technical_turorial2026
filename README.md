# Technical Tutorial — 15th September 2026
Chemprop for Peptide Property Prediction: Multitask Learning, Pretraining, and Fine-Tuning

This repository contains the material for the technical tutorial on applying multitask learning, pretraining, and transfer learning to low-quality and low-data datasets, focusing on peptide properties prediction.
The examples presented here are a simplified, 'tiny' version of some of the approaches developed as part of the [PePcube project](https://github.com/elee151/pepcube_property).

## Repository Structure 
The repository is organised around four practical notebooks:
* **Notebook 1** — Single-Task vs. Multitask Learning
Introduction to [Chemprop](https://pubs.acs.org/jcisd8/article/64/1/9/850416/Chemprop-A-Machine-Learning-Package-for-Chemical) and comparison between single-task and multitask models for peptide property prediction.
* **Notebook 2** — Multitask Pretraining Exercise
A hands-on exercise to train a multitask model on calculated scores representing proxy peptide properties.
15K peptides entries, only natural amino acids sequences are used as input for the pretraining model.
* **Notebook 3** — Transfer Learning and Fine-Tuning
Application of transfer learning by starting from the in-house pretrained model and fine-tuning it on the 'experimental' targets.
* **Notebook 4** — Chemeleon Pretraining
Pretraining using [Chemeleon](
https://pubs.acs.org/jcisd8/article/doi/10.1021/acs.jcim.6c01546/5250516/Deep-Learning-Foundation-Models-for-Low-Data), optimised for molecular properties predictions.

## Data and Models
The `data/` folder contains the datasets for training and evaluation.
Pretrained models are saved in the `models/ folder`.

> [!IMPORTANT]
> If you would like to use [Chemprop](https://pubs.acs.org/jcisd8/article/64/1/9/850416/Chemprop-A-Machine-Learning-Package-for-Chemical) or [Chemeleon](
https://pubs.acs.org/jcisd8/article/doi/10.1021/acs.jcim.6c01546/5250516/Deep-Learning-Foundation-Models-for-Low-Data), or explore these tools further, additional tutorials can be found in their original repositories:
> [https://chemprop.readthedocs.io/en/main/notebooks.html](https://chemprop.readthedocs.io/en/main/notebooks.html)
> [https://github.com/JacksonBurns/chemeleon](https://github.com/JacksonBurns/chemeleon)
