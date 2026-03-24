# 🧪 Lab 04: Training CNNs (AlexNet & ResNet)

## 📖 Overview
This lab explores two milestone Convolutional Neural Network architectures: AlexNet and ResNet. The session focuses on understanding their structural differences, implementing them, and performing hyperparameter tuning to optimize model performance.

## 🧠 Key Concepts Covered

* **AlexNet:** Understanding the architecture that popularized deep learning in computer vision, featuring 5 convolutional layers, max pooling, and 3 fully-connected layers.
* **ResNet & Residual Connections:** Addressing the vanishing gradient problem in deep networks. This covers how residual blocks allow gradients to flow through "identity shortcuts," making it possible to train networks with dozens or hundreds of layers without performance degradation.
* **Hyperparameter Tuning:** Strategies for finding the best model configuration. This involves splitting data into train/validation/test sets and experimenting with:
  * Learning Rates (e.g., 0.1, 0.001, 0.0001)
  * Batch Sizes (e.g., 16, 32, 64)
  * Weight Decay (regularization)

## 💻 Exercises and Notebooks

The practical component tasks you with training these advanced architectures on the TinyImageNet dataset. 

* **AlexNet Implementation:** Train an AlexNet network and perform a grid search over different learning rates and batch sizes to observe the effects on accuracy.
* **ResNet Implementation:** Apply the same hyperparameter search to a Deep Residual Network and compare the optimization process and final accuracy against AlexNet.

## 🚀 Running the Code
Open the provided Colab notebook and ensure hardware acceleration is enabled (Runtime > Change runtime type > GPU) as training these deeper networks is computationally intensive.
