# BYOL tutorial: self-supervised learning on CIFAR images with code in Pytorch

After presenting SimCLR, a contrastive self-supervised learning framework, I decided to demonstrate another infamous method, called BYOL. Bootstrap Your Own Latent (BYOL), is a new algorithm for self-supervised learning of image representations. BYOL has two main advantages: 
It does not explicitly use negative samples. Instead, it directly minimizes the similarity of representations of the same image under a different augmented view (positive pair). Negative samples are images from the batch other than the positive pair.
As a result, BYOL is claimed to require smaller batch sizes, which makes it an attractive choice.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/16Mjujx6aLZX7wcge_2Xca0NdQyrONPA1?usp=sharing)
