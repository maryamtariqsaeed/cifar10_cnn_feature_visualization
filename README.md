# cifar10_cnn_feature_visualization

This project builds and trains a Convolutional Neural Network (CNN) using TensorFlow/Keras to classify images from the CIFAR-10 dataset.

## Dataset

CIFAR-10 is a popular computer vision dataset containing:

* 60,000 color images
* Image size: 32 × 32 pixels
* 10 object classes

Classes included:

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

## Model Architecture

The model is a deep CNN with the following features:

* Data Augmentation
* Convolutional Layers
* Batch Normalization
* LeakyReLU Activation
* MaxPooling Layers
* Dropout for regularization
* L2 Weight Regularization

### Training Techniques

* Adam Optimizer
* Early Stopping
* Reduce Learning Rate on Plateau

## Feature Map Visualization

The project visualizes intermediate feature maps from convolutional layers to observe what the CNN learns during training.

## Results

Test Accuracy achieved: **~84%**

## Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib

## How to Run

1. Clone the repository

```
git clone https://github.com/maryamtariqsaeed/cifar10-cnn-feature_visualization.git
```

2. Install dependencies

```
pip install -r requirements.txt
```

3. Run the notebook

Open the notebook in **Jupyter Notebook or Google Colab** and execute the cells.

## Project Structure

```
cifar10-cnn-feature_visualization
│
├── cifar10-cnn-feature_visualization.ipynb

├── README.md
└── requirements.txt
```
