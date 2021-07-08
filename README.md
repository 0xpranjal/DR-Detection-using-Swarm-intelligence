# Swarm-Research

## Training plan for image models(Without Swarm Optimisation)
* The models would be trained on the 2015 Kaggle Competition dataset-> [Link](https://www.kaggle.com/c/diabetic-retinopathy-detection)
* The images in the dataset have an irregular size so we use the dataset -> [Link](https://www.kaggle.com/benjaminwarner/resized-2015-2019-blindness-detection-images)
* Total number of images is 35000 and we apply 5 fold stratified K Fold Validation.

* Models to be covered
   * Efficientnet B5
   * Resnet 200D
   * **Add in your suggestions here**

 ## Deep Swarm(Swarm based optimisation for finding optimal Neural Network Architecture using Ant Colony Optimisation)
   * Checked for compatibility of Code in TF 2.x using MNIST Pipeline
   * Pipeline ready for training, the image size and some hyperparameters are to be decided now
   * [Paper](https://arxiv.org/abs/1905.07350)     

 ## psoCNN
   * Completed pipeline, hopefully works -> Small issue while running on instance with regards to loss and softmax
   * Dataset path to be modified in psoCNN.py -> Done but does not use the stratified kfold as of now. Uses the raw dataset
   * Need to decide on hyperparameters
   * [Reference paper](https://www.sciencedirect.com/science/article/abs/pii/S2210650218309246)
   * Pipeline taken from [here](https://github.com/feferna/psoCNN)
   * [This](https://www.kaggle.com/xhlulu/aptos-2019-densenet-keras-starter) kaggle kernel was also referenced a bit

 ## LDWPSO CNN (Linearly Decreasing Particle Swarm Optimization Convolutional Neural Network)
   * The program rewrites and uses part of the Hyperactive library
   * Tested on MNIST
   * [Paper](https://arxiv.org/abs/2001.05670)
  
