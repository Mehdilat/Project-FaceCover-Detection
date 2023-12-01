# Face Classification using a Pre-trained VGGFace Model

The project employs a Convolutional Neural Network (CNN) using transfer learning, specifically a pre-trained VGGFace model, for binary facial classification. The model is adapted for a two-class problem, and its preprocessing includes image resizing and normalization. To address class imbalance, a random weighted sampler and image augmentation techniques (like horizontal flips, rotations, jitter, and gaussian blur) are used during training. The CNN model is initialized with frozen backbone layers, and various training parameters are set, such as epochs, batch size, and learning rate.

The used VGGFace model and weights can be found in the following link: https://www.robots.ox.ac.uk/~albanie/pytorch-models.html
