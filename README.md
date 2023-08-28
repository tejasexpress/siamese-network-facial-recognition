# Facial Recognition Using Siamese Network

This repository contains the code and resources for building a facial recognition system based on a Siamese neural network architecture. The Siamese network is a type of neural network specifically designed for tasks involving similarity or dissimilarity comparison between input pairs. In this project, we leverage the power of Siamese networks to perform facial recognition tasks.

The Siamese network architecture consists of two identical subnetworks (twins), each taking one input image. The outputs of these subnetworks are then combined to calculate the similarity score between the input images. The network is trained using a contrastive loss function that encourages similar images to have a smaller distance and dissimilar images to have a larger distance.

You can expect the Siamese network to achieve competitive results with relatively few training samples.

# Dependencies

* Python (>= 3.6)
* Jupyter Notebook
* TensorFlow (>= 2.0)
* NumPy
* OpenCV
* Matplotlib

# Dataset

For this project, we use the Labeled Faces in the Wild (LFW) dataset, which contains a diverse set of labeled face images. The dataset is preprocessed to generate pairs of images with corresponding labels (same person or different persons).
