# Computer Vision and Object Recognition

In this repository, you'll find the labs and final projects from the corresponding [ENS Ulm](http://www.ens.fr/en/ens/facts-and-rankings/international-rankings) course by Pr. [Jean Ponce](https://www.linkedin.com/in/jean-ponce-2302986/?originalSubdomain=fr), [Ivan Laptev](https://www.di.ens.fr/~laptev/), and [Cordelia Schmidt](https://www.linkedin.com/in/cordelia-schmid-47985a9/?originalSubdomain=fr), 2019 edition.

The topics covered are the following ones:

1. Lab1: Introduction to Local Invariant Features using [Scale Invariant Feature Transform: SIFT](https://en.wikipedia.org/wiki/Scale-invariant_feature_transform) points of interests, image matching using [Bags of Visual Words: BOVW](https://towardsdatascience.com/bag-of-visual-words-in-a-nutshell-9ceea97ce0fb). Given a picture of a portion of a painting and a database of scans of paintings, identify the original picture.

2. Lab2: Introduction to [Convolutional Neural Network](http://cs231n.github.io/convolutional-networks/): [convolution operation](https://en.wikipedia.org/wiki/Convolution), backpropagation of the gradient, pooling, multiple layers, drops, non-linear activation functions, training on [CIFAR 10](https://en.wikipedia.org/wiki/CIFAR-10) and [MNIST](http://yann.lecun.com/exdb/mnist/).

3. Final project: Studying and experimenting with [CycleGANs](https://junyanz.github.io/CycleGAN/). It's about style transfer and high level properties transfer from a set of images to another one. Example: convert any image of a landscape taken in the summer to its winter counterpart. In this study, I investigate a pytorch implementation of the cycleGAN: I reproduced some of the results of the paper, applied the CycleGAN on two new datasets for real face to cartoon and sad to happy image translation. I also played with the loss functions to highlight the importance of each loss member and its effect.
