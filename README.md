# Shaurya_StaquSVHN
Experiment with SVHN dataset
# Summary
## 1. Experiments with the architecture
* This notebook contains all the Pre-processing method i.e need to prepare data for training.
* I have experimented with the architecture to improve the performance of my architecture.
* I started with the basic model and make other models by adding layers/regularization to my basic model.
## 2. Using Data Augmentation
* In this notebook, I tried a Data Augmentation with the model (model5) which gives me the best performance in my previous experiment.
* Augmentation makes it harder to memorize the data and get high training scores,that's it's purpose. So getting a higher test accuracy than training accuracy isn't a bad sign.
## 3. K-fold evaluation
* In this notebook, I tried to evaluate my CNN architecture(model5) by using startifie-k-fold.
## 4. Using Transfer- learning
* In this notebook, First I trained a CNN architecture on MNIST dataset and then used that weights to train model on SVHN datasets.
