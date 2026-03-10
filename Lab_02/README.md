# 🧪 Lab 02: Training a Custom Model

## 📖 Overview
This lab covers the essential workflow for training deep learning models using PyTorch. The session transitions from basic tensor operations to constructing, training, and evaluating fully functional neural networks from scratch.

## 🧠 Key Concepts Covered

* **The PyTorch Workflow:** Understanding the end-to-end machine learning pipeline, from preparing data and building architectures to evaluating results and saving the finished model.
* **Hardware Acceleration:** Managing devices efficiently by checking for GPU availability (CUDA) and transferring tensors and models to the appropriate hardware for faster computation.
* **Network Architecture (`torch.nn.Module`):** The standard methodology for creating custom neural networks. This involves subclassing the base module, defining individual layers within the initialization function, and scripting the forward propagation logic.
* **Loss Functions:** Measuring model error by comparing network predictions against actual target labels using standard mathematical functions, such as Cross-Entropy for classification tasks.
* **Optimization & Backpropagation:** Utilizing gradient descent algorithms (like SGD) to minimize the loss. This covers the critical steps of clearing previous gradients, calculating new gradients via backpropagation, and stepping the optimizer to update network weights.
* **Model Persistence:** Best practices for saving and loading trained network parameters using PyTorch state dictionaries.

## 💻 Exercises and Notebooks

The practical component requires you to bring all these concepts together to build a complete classification pipeline.

* **Custom Architecture:** Design a neural network tailored for image classification.
* **Training & Testing Loops:** Write the core iteration loops that handle batch processing, forward passes, loss calculation, and weight updates.
* **TinyImageNet Application:** Train your custom model on the TinyImageNet dataset and evaluate its final accuracy on unseen test data.

## 🚀 Running the Code

Open the Colab notebook provided in this folder. To ensure the training loop runs efficiently, remember to enable hardware acceleration (Runtime > Change runtime type > T4 GPU) before executing the cells.
