# Generative-Adversarial-Network-(GAN)-on-MNIST-Dataset
In this project, I have applied Generative Adversarial Network (GAN) on MNIST Dataset. 
I have used Hyper-parameter Tuning along with Precision and Recall.
3 Activation Functions are being used - ReLU, ELU, SELU .
2 Learning Rates are being used - 0.0001, 0.0002 .
2 Optimizers are being used - Adam, SGD .
Now, Discriminator and Generator Losses are calculated along with Precision and Recall for different combinations of the above parameters.
3 plots are drawn for each of the epochs, namely Generator & Discriminator Loss, Precision and Recall.
Finally, the Best Configuration is identified.
In this project, the Best Configuration came to be the Activation Function ReLU, Optimizer SGD with a Learning Rate of 0.0002, with an Average Precision of 1.0000 .
