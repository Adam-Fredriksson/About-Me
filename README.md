# About Me
Since many of the projects I have worked on are related to my education or research, the code can not be made public. This can be due to code of conduct regarding assignments, or because the code is not yet ready to be released. However, here I will present some of the projects that I have worked on and explain a little bit about what I did, what I learned and what results I got.

# Machine Learning Projects With PyTorch
* __Diffusion Model__: This project is currently the only public repository and was part of a Deep Learning course at KTH. In this project, we implemented a Denoising Diffusion Probabilistic Model (DDPM) that could generate images both unconditionally and by using class conditioning. The class conditioning was improved by utilizing classifier-free guidance. Moreover, we implemented a novel, to the best of our knowledge, architecture in the context of DDPMs. The novelty was to use a U-Net with both self-attention and cross-attention, quite similarly as is done in Transformers. The cross-attention is the novelty, and is calculated between the residual connections from the downward pass of the U-Net. Typically, these are only concatenated with the upsampled images, but we added cross-attention as well. My role in this project was to implement the actual architecture and to implement the training and sampling functions. This yielded a good understanding of diffusion models and how to implement and test complex architectures.

* __Quantum Physics__: This is a current research project, so I am unable to share explicit details yet!

# Machine Learning Projects From Scratch (i.e. using only Numpy and implementing networks, optimizers, analytical gradients etc. completely from scratch)
* __K-layer network__: K-layer networks has been implemented from scratch, meaning the gradients are analytically implemented. The model were trained with a cyclic learning rate on CIFAR10, and reached a classification accuracy of around 52%.
* __Batch Normalization__: K-layer networks with batch normalization has been implemented from scratch, meaning the gradients are analytically implemented. The model were trained with a cyclic learning rate on CIFAR10, and reached a classification accuracy of around 54%.
* __Optimizers__: I have implemented several optimizers from scratch. These are: Adam, Adagrad, SGD, RMSprop and Nesterov Accelerated Gradient.
* __Recurrent Neural Network (RNN)__: Implemented an RNN that trained on Harry Potter The Goblet of Fire. More complex sampling such as Temperature Sampling and Nucleus Sampling was implemented as well.

# Machine Learning Project With Tensorflow
* __Quantum Physics (Bachelor Thesis)__:
