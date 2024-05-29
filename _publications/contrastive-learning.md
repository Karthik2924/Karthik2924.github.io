---
title: "CONTRASTIVE CURRICULUM AUGMENTATION FRAMEWORK FOR SELF-SUPERVISED LEARNING"
collection: publications
permalink: /publication/contrastiveLearning
excerpt: 'This paper is about leveraging unlabelled data to pretrain the model using contrastive learning methods with a curriculum which sequentially increases the difficulty of the training examples.'
date: 2022-09-17
venue: 'International Journal of Soft Computing and Artificial intelligence Volume-10, Issue-1'
#slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://www.researchgate.net/publication/363767138_CONTRASTIVE_CURRICULUM_AUGMENTATION_FRAMEWORK_FOR_SELF-SUPERVISED_LEARNING#fullTextFileContent'
citation: 'Priyam Garg ,Sanka Karthik ,Annie Uthra , (2022 ) " Contrastive Curriculum Augmentation Framework for Self-Supervised Learning " , International Journal of Soft Computing And Artificial Intelligence (IJSCAI) , pp. 5-9, Volume-10,Issue-1'
---

With increase in unstructured data everyda, learning underlying structure of data has become rather important compared to the alternative of manually labelling data which is very costly. The primary goal of self-supervised learning methods is to capture the fundamental representations of data regardless of labels. In a contrastive learning setting, we have created a curriculum augmentation framework and trained a dual network with the help of that framework. Our framework gradually updates augmentation parameters within a set limit and progressively make the images harder to classify for every successive iteration. We divided our framework into static composure and dynamic composure sub parts and found static composure works better because of comparatively less catastrophic forgetting than dynamic composure. We have shown in our experiments that our curriculum augmentation framework indeed works better than standard augmentations. We also developed ProAug which supports our novel curriculum augmentation framework in both supervised and self-supervised training paradigm.