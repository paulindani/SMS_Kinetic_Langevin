This repository contains the code for reproducing the experiments of the paper "Sampling from Bayesian Neural Network Posteriors with Symmetric Minibatch Splitting Langevin Dynamics" by Paulin, Whalley, Chada and Leimkuhler.

The individual files contain the following:
bias_test_wass.ipynb - Wasserstein bias estimates for the 1D example in Section 3.4
CelebA_SMS_UBU.ipynb - SMS-UBU experiments for CelebA dataset
chestxray_SMS_UBU.ipynb - SMS-UBU experiments for chest X-ray dataset
fashion_MNIST_cyclic_SG_HMC.ipynb - experiments for Fashion-MNIST dataset with cyclical SG-HMC
fashion_MNIST_SG_HMC.ipynb - experiments for Fashion-MNIST dataset with SG-HMC
fashion_MNIST_SG_HMC-without_replacement.ipynb - experiments for Fashion-MNIST dataset with SG-HMC with batches sampled without replacement
fashion_MNIST_SG_UBU.ipynb - experiments for Fashion-MNIST dataset with SG-UBU 
fashion_MNIST_SG_UBU_without_replacement.ipynb - experiments for Fashion-MNIST dataset with SG-UBU with batches sampled without replacement
fashion_MNIST_SMS_UBU.ipynb - SMS-UBU experiments for Fashion-MNIST dataset
multinomial_SMS_UBU.ipynb - Bias experiments from Section 3.4 for Bayesian multinomial regression on Fashion-MNIST dataset
