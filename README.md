# Project Description
Worked on optimizing a Mini-VGG network for image classification using the CIFAR-10 dataset in a GPU environment. The project involved extensive experimentation with different model architectures and hyperparameters to achieve improved performance. The key steps included:

Base Model (Mini-VGG): Developed a convolutional neural network using ReLU activation. The best model after applying data augmentation and batch normalization achieved an accuracy of 89.79% with 3.25M learnable parameters.

Model Variants:

Activation Function Variants: Replaced ReLU with SELU and Swish activations. The Swish-activated model performed the best with 89.96% accuracy.
Architecture Tweaks: Removed max-pooling and used strided convolutions, increasing the number of learnable parameters to 9.54M, resulting in 89.35% accuracy.
Dropout Implementation: Applied dropout after fully connected layers and after each convolution layer. Dropout after fully connected layers resulted in the highest accuracy of 90.52%.
Optimization Techniques: I applied data augmentation, batch normalization, and dropout with Adam optimizer. Various learning rates and weight decays were tested, optimizing the training process.

This project allowed me to fine-tune a deep learning model while experimenting with state-of-the-art techniques like Swish activation and dropout scheduling, achieving an accuracy of 90.52%.
