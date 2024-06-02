# CS 189 hw 6 <br><br> Name: Tony de Leon, <br>  Student ID: REDACTED

## Question 4: Basic Network Layers

All work can be found in the expected locations 
(ReLU = activations.py ReLU class, Fully-Connected Layer = layers.py FullyConnected class, etc.)

## Question 5: Two-Layer Fully Connected Networks

All working can be found in expected locations <br>
Note that the hyperparameters I tested are: <br>
1. 25 hidden layers, 0.01 learning rate $\longrightarrow$ 0.3021 test loss, 0.88 test accuracy, 0.12 test error
2. 125 hidden layers, 0.01 learning rate $\longrightarrow$ 0.0797 test loss, 0.96 test accuracy, 0.04 test error
3. 125 hidden layers, 0.004 learning rate $\longrightarrow$ 0.1102 test loss, 0.96 test accuracy, 0.04 test error

## Question 6: CNN Layers

### 6.1: The Einsum Function

I created a new file, Einsum.ipynb, for this question. I additionally used this file to place the markdown created by running "python3 generate_submission.py --f markdown  --heading_level 2 --o code.md", sorry if this causes any confusion

The rest of the work for this question can be found in the expected locations

## Question 7: PyTorch

All work for this question can be found in CS189_HW6_NN.ipynb. I apologize for the large amount of training prints.

### Question 7.2: CNNs for CIFAR-10

NOTE: The current state of the notebook is a recreationg of the setup I used to get my kaggle model. I ran many experiments after getting my best kaggle submission but was never able to get a validation accuracy high enough to exceed my kaggle model. Thus, the current output of the cells are not produced by my current kaggle model. However, I went back and changed the parameters of the model, transforms, epochs, learning rate, etc. to get as close to the parameters as I could for my kaggle model. Its possible I missed a detail but I don't believe I did.

I apologize that the file is not currently in the state it was to create the kaggle and appreciate your understanding. Note that I manually ran a few epochs at the end of my kaggle model's training to get a validation accuracy of about 91.77% if I remember correctly.

Additionally, while I included this in my code itself, I want to include the sources I used when designing my model architecture here as well to ensure it's clear how I arrived at the base architecture I used and built upon:
1. https://arxiv.org/abs/1512.03385 Original ResNet paper
2. https://arxiv.org/abs/1603.05027 Slight innovation in the Residual Blocks: Pre-Activation


Kaggle Username: Tony de Leon <br>
Kaggle Score: 0.924 

(I have no idea how Johan has 0.963... Thats crazy)
