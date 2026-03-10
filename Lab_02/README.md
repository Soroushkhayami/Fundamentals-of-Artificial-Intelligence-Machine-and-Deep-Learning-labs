# 🧪 Lab 02: Training a Custom Model

## 📖 Overview
[cite_start]This lab focuses on the PyTorch workflow for building and training a custom neural network[cite: 472, 474]. [cite_start]You will learn how to define a model architecture, select appropriate loss functions and optimizers, and write full training and testing loops[cite: 486, 487, 593, 608].

## 🧠 Key Concepts Covered

* [cite_start]**PyTorch Workflow:** The end-to-end process includes getting data ready, building a model, fitting it to the data, evaluating performance, improving through experimentation, and saving the results[cite: 479, 480, 481, 482, 483, 484].
* [cite_start]**Device Management:** Using `torch.cuda.is_available()` to seamlessly move models and data to hardware accelerators like GPUs for faster training[cite: 489, 490].
* **Defining the Model (`torch.nn.Module`):** The foundational blueprint for neural networks. [cite_start]We cover subclassing `nn.Module`, initializing layers within `__init__`, and implementing the forward pass operations in the `forward` method[cite: 495, 496, 504, 505].
* [cite_start]**Loss Functions:** Determining model performance by comparing prediction outputs to target values using functions like `nn.MSELoss` (for regression) or `nn.CrossEntropyLoss` (for classification)[cite: 556, 567, 568].
* [cite_start]**Optimizers & Autograd:** Using optimizers like `torch.optim.SGD` to adjust internal parameters to lower the loss[cite: 573, 575]. [cite_start]This leverages PyTorch's Autograd package for automatic differentiation (`loss.backward()`), updating parameters (`optimizer.step()`), and resetting gradients (`optimizer.zero_grad()`)[cite: 578, 580, 581, 586].
* [cite_start]**Saving and Loading Weights:** Persisting learned parameters using the model's internal state dictionary (`state_dict`), `torch.save()`, and `load_state_dict()`[cite: 639, 640, 642, 643].

## 💻 Exercises and Notebooks

[cite_start]The practical component tasks you with implementing a complete neural network pipeline from scratch[cite: 648]. 

* [cite_start]**TinyImageNet Classification:** Build a custom neural network to classify images from the TinyImageNet dataset[cite: 649, 652].
* [cite_start]**Custom Loops:** Implement the full PyTorch training loop and test loop[cite: 653].
* [cite_start]**Evaluation:** Track the loss and evaluate the final training and test accuracy achieved by your custom network[cite: 655, 656].

## 🚀 Running the Code

Open the Colab notebook provided in this folder. Make sure to change your runtime to GPU (Runtime > Change runtime type > T4 GPU) to take advantage of PyTorch's CUDA acceleration during the training loop.
