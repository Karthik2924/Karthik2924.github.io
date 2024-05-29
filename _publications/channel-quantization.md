---
title: "Latent Disentanglement via Channel Quantization for Discrete Interpretable Embeddings"
collection: publications
permalink: /publication/channel-quantization
excerpt: 'This paper tackles the problem of lack of interpretablility in codewords of a VQVAE model and achieves higher compression ratios with a very minimal use of labeled data.'
date: 2021-07-06
venue: 'Under Review'
#slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
#paperurl: 'https://drive.google.com/file/d/1rslFjlpGMGNKffGqR5umrDYLpHcboG8U/view' #'http://academicpages.github.io/files/paper1.pdf'
citation: 'Karthik Sanka, Jung-Eun-Kim,(2024) Latent Disentanglement via Channel Quantization for Discrete Interpretable Embeddings'
---

 Disentangled representation learning is an important step in addressing spurious correlations and improving the interpretability of deep learning models. In this paper, we tackle the problem of disentangling attributes or sources of generation in the latent space of a vector quantized variational autoencoder model by adopting certain inductive biases to the model architecture based on the dataset. We accomplish this by structuring the codebook to match the distribution of the data. We learn a mapping from data to codebooks via a group convolutional neural network. Each group learns a different attribute/source of the dataset and is quantized to a different codebook. Each of the codebooks contains codewords that correspond to different states/values an attribute can take. We learn the mapping from each data point to corresponding codewords by making use of labels. The training procedure is divided into two stages: 1) Supervised disentanglement and 2) Unsupervised fine tuning. We observe impressive results on many different disentanglement datasets. Our proposed method and framework are able to learn disentangled representation using a small subset (1\%) of labeled data, and are able to generalize to unseen combinations of generative factors. We emphasize that our framework can effectively advance interpretability in vision models and can also be extended to other modalities as well.

