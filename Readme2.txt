# Manipulated Facial Image Detection using Deep Learning

Overview

This project titled "Manipulated Facial Image Detection using Deep Learning" aimed to address the increasing concerns surrounding the authenticity and integrity of visual media, particularly in the context of facial image manipulation using software like Face swap, deepfakes, and Face2Face. The project employed deep learning techniques, specifically focusing on a pre-trained ResNet34 model, to develop a robust system capable of detecting and identifying manipulated facial images.

Project Structure

1. Libraries

Installs and imports necessary libraries such as PyTorch, torchvision, wandb, and others.

2. Data Loading and Preprocessing

Defining data directories for training, validation, and testing.
Setting up data transformations for augmentation.
Creating data loaders for training, validation, and test sets.

3. Visualization

Includes a visualization section for displaying sample images from the dataset as a sanity check for data augmentation.

4. Network Architecture

Defines the SeResNetNetwork class, creating an instance of the SeResNet model using the timm library.
Moves the model to the GPU if available and calculates the total number of parameters.

5. Training

Implements the training process, including the train function for training the model and the validate function for evaluating on the validation set.
Utilizes mixed precision training for efficiency.
Incorporates a learning rate scheduler to adaptively adjust the learning rate during training.

6. Wandb Integration

Integrates with Weights & Biases for experiment tracking and visualization of training and validation metrics.

7. Testing

Defines the testing process using the test function for evaluating the model on the test set.
Calculates and prints the test accuracy achieved by the trained model.

8. Results

Prints the final test accuracy achieved by the model.
