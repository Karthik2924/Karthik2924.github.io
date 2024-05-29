---
layout: archive
permalink: /projects/
title: "Projects"
author_profile: true
redirect_from:
  - /projects
showTableOfContents: true
---
## Table of Contents
- [Motif Finding](#motif)
- [Self Supervised Learning](#ssl)
- [Fake news detection](#hackathon)
- [Mental Health app](#hackathon2)

<a id="motif"></a>
## Discovering DNA Motifs Using Particle Swarm Optimization with Sequence Preprocessing

* Motif Finding Problem :
  * The process of discovering patterns in a collection of sequences, such as DNA sequences.
  * Given : DNA sequences, no prior knowledge about where a motif could be in each sequence.
  * Output : Motifs with different number of mutations allowed.
* Motif finding problem is an NP-complete problem. Due to the size and the number of DNA sequences in practice, it is often intractable to use conventional brute force search methods to solve this problem.
* This work adopts Particle Swarm Optimization, a nature inspired metaheuristic optimization to solve Motif Finding problem.

The project github repository can be found [here](https://github.com/Karthik2924/CSC530_project)

![Poster of Our project](/images/pso.png)

<a id="ssl"></a>
## Self Supervised Learning
Contrastive Curriculum Augmentation Framework for Self-Supervised Learning 
- Designed and implemented a novel contrastive self-supervised learning model with a curriculum augmentation framework.
- Increased the difficulty of the images slowly with our framework by controlling the strengths of the augmentations during training.
- Achieved improvement in accuracy by 15% from the baseline on CIFAR100 dataset.
- Published our findings in IJSCAI. [Paper Link](https://www.iraj.in/journal/journal_file/journal_pdf/4-836-16634018505-9.pdf)

<a id="hackathon"></a>
## Fake News Detection

Detect Fake News/Information
- Developed an application that will help determine if given information is fake or real by leveraging Large Language models and web scraping.
- Used OpenAI’s whisper from huggingface to convert Video/Audio input into text and use Gemini API from Google Cloud Platform, to
summarize the information and extract the claims made in the article.
- We scrape multiple web sources for the claims made in the article and summarize them using the Large Language Model and provide the user
with the information as well as the source.

<a id="hackathon2"></a>
## BLISS - Mental Health App

- Detects signs of mental health problems such as depression by noting responses from the user.
- My Contribution : Trained the machine learning model on publicly available dataset.
- Deployed an API that instantiates the model on Heroku for simple integration with the application.

