CNN for CIFAR-10 Image Classification

A beginner-friendly deep learning project built using PyTorch to classify images from the CIFAR-10 dataset using a Convolutional Neural Network (CNN).

This project was created as part of my deep learning learning journey to understand how CNN architectures work for image classification tasks. It covers the complete pipeline from dataset loading and preprocessing to training and evaluation.

⸻

Project Overview

The goal of this project is to train a CNN model that can recognize and classify images into 10 different categories from the CIFAR-10 dataset.

The project includes:

* Loading and preprocessing the CIFAR-10 dataset
* Building a custom CNN architecture using PyTorch
* Training the neural network
* Evaluating model accuracy on test data
* Understanding core CNN concepts like convolution, pooling, activation functions, and fully connected layers

⸻

About CIFAR-10

CIFAR-10 is a popular benchmark dataset in computer vision.

It contains 60,000 color images of size 32x32 divided into 10 classes:

* Airplane
* Automobile
* Bird
* Cat
* Deer
* Dog
* Frog
* Horse
* Ship
* Truck

Dataset split:

* 50,000 training images
* 10,000 testing images

⸻

Tech Stack

* Python
* PyTorch
* Torchvision
* Google Colab / Jupyter Notebook

⸻

CNN Architecture

The model uses:

Convolution Layers

Extract important spatial features from images.

ReLU Activation

Adds non-linearity to the network.

Max Pooling

Reduces image dimensions while preserving important features.

Fully Connected Layers

Performs final classification into 10 classes.

⸻

Project Structure

CNN_for_CIFAR10.ipynb
README.md

⸻

Installation

Clone the repository:

git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

Install dependencies:

pip install torch torchvision

⸻

Running the Project

Open the notebook:

jupyter notebook CNN_for_CIFAR10.ipynb

Or run it directly in Google Colab.

⸻

Training

The model is trained using:

* Loss Function: CrossEntropyLoss
* Optimizer: Adam
* Epochs: 10
* Batch Size: 64

During training, the notebook prints:

* Epoch-wise training loss
* Model learning progress

⸻

Evaluation

After training, the model is evaluated on the CIFAR-10 test dataset.

The notebook calculates:

* Prediction accuracy
* Correct vs total classified images

⸻

Learning Outcomes

Through this project, I learned:

* Fundamentals of Convolutional Neural Networks
* How image tensors work in PyTorch
* Data preprocessing using torchvision transforms
* Forward propagation and backpropagation
* Model evaluation techniques
* Training deep learning models using GPUs/CPUs

⸻

Future Improvements

Some future improvements I plan to add:

* Data augmentation
* Batch normalization
* Dropout layers
* Learning rate scheduling
* Model checkpoint saving
* TensorBoard visualization
* Transfer learning with pretrained models

⸻

Sample Concepts Used

Image Normalization

transforms.Normalize((0.5, 0.5, 0.5), (0.5, 0.5, 0.5))

CNN Layers

nn.Conv2d()
nn.ReLU()
nn.MaxPool2d()

Optimizer

optim.Adam(model.parameters())

⸻

Why I Built This

I built this project to strengthen my understanding of deep learning and computer vision using PyTorch. This project helped me move from theoretical ANN concepts to practical CNN implementation on real image datasets.

It is part of my AI/ML learning journey where I am consistently building projects while learning advanced deep learning concepts.

⸻

Author

Shiv Gupta

AI/ML Enthusiast | Deep Learning Learner | Building Projects in Public

GitHub: https://github.com/shivgupta69

⸻

License

This project is open-source and available under the MIT License.
