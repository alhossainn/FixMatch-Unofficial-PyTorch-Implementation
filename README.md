# FixMatch-Unofficial-PyTorch-Implementation
This is an unofficial implementation of ["FixMatch: Simplifying Semi-Supervised Learning with Consistency and Confidence"](https://arxiv.org/abs/2001.07685) using PyTorch. 

This code is implemented using <b>Google Colab Pro T4 GPU</b>, and the RandAugment function utilized in this code can be found [here](https://github.com/alhossainn/Data-Augmentation-Techniques-for-Image-Processing).

FixMatch is a semi-supervised learning algorithm that combines pseudo-labeling and consistency regularization to improve neural network performance with minimal labeled data. It leverages a small amount of labeled data and a large amount of unlabeled data to improve model performance. The key idea is to generate pseudo-labels for weakly augmented unlabeled data and train the model using these pseudo-labels on strongly augmented versions of the same data.  <br> FixMatch achieves state-of-the-art results in various benchmark datasets.

The official implementation in TensorFlow can be found [here](https://github.com/google-research/fixmatch).
