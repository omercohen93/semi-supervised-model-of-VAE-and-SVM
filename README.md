# semi-supervised-model-of-VAE-and-SVM
 semi-supervised learning via a variational autoencoder, a part of the paper "Semi-supervised Learning with Deep Generative Models", by Kingsma et al.

This file demonstrates a way of encoding images using VAE, such that a small amount of labeled data is sufficient to get decent training of classification model with SVM.
The data  used is Fashion MNIST.

The notebook runme.ipynb contains all the code used to train and evaluate
the different networks and the graphs.

## To run a test using the saved models:  Run all the runme file.

·         First we mount the drive, to get access. Under the "mount drive" headline press the link, approve and copy the code.
·         If you run the folder at a specific location in an internal folder in your drive, please specify its path in the variable "your_path".
·         rest of the code runs independently
 
Every section in the test part creates an appropriate model and loads the weight file.
If you want to see the training process: To train The VAE delete the relevant hash in parameters section. To train The SVM delete the relevant hash in: SVM - Define model section.

## Results
| Number of labeled data training samples  | Error rate |
| ------------- | ------------- |
| 100  | 33.1%  |
| 600  | 20.9%  |
| 1000  | 19.4% |
| 3000  | 16.1% |
