# Sketch-Detector

# Introduction
Image retrieval using hand-free sketches drawn by amateurs is an interesting and challenging problem. In this project, Siamese network has been employed to learn the similarity between a sketch-photo pair. For a given sketch the model searches the most closely matched photos from a large image dataset.

# Overview
A sketch speaks a “hundred” of words, which makes it a more efficient and precise query modality (e.g. shape, pose, style of a handbag) than text. Words are not always the most convenient way to describe the exact object people want to search, especially when it comes to fine-grained object details.

The main idea is to pull output feature vectors closer for input sketch-image pairs that are labeled as similar, and push them away if irrelevant. This is implemented in code using a 'contrastive' loss function.
