# Siamese Network for Few-Shot Learning

This repository contains the implementation of a Siamese Network for few-shot learning using the mini-ImageNet dataset. The project demonstrates the ability to recognize unseen classes with only a few labeled examples by training on contrastive and triplet losses.

## Features

- **Custom Siamese Network**: Built from scratch to generate embeddings for similarity comparison.
- **Pretrained ResNet-18 Baseline**: Fine-tuned on contrastive and triplet losses for comparison.
- **Evaluation**: Conducted on 5-way 1-shot, 4-shot, 8-shot, and 16-shot tasks with metrics:
  - Top-1 and Top-5 Accuracy
  - Mean Average Precision (mAP)
- **Visualization**: t-SNE or PCA plots to observe embeddings.

## Dataset

The mini-ImageNet dataset contains 100 classes split into training, validation, and test sets. Images are resized to 224x224 for this implementation.
https://www.kaggle.com/datasets/arjunashok33/miniimagenet
