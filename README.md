# Transfer Learning in PyTorch

## Project 1: Transfer learning (PyTorch).ipynb

The notebook contains the final project of **PyTorch Scholarship Challenge** from Udacity and facebook.

The 102 Category Flower [Dataset](http://www.robots.ox.ac.uk/~vgg/data/flowers/102/index.html) from Visual Geometry Group, University of Oxford, is used.

The following **steps** are described:
* Preprocessing
* Transfer learning
* Saving and loading model checkpoint
* Inference and Validation

**Analysis:**
* Model used: ResNet101
* Epochs trained: 20
* Validation accuracy: 94.13%
* Optimizer used: Adam
* Loss used: CrossEntropyLoss
* Scheduler used: StepLR
* Device used: cuda
* Comments: `fc` layer replacement with combination of linear layers with Dropout regularization 

**NOTE:** *If the notebook doesn't render here on GitHub, try it on [nbviewer](https://nbviewer.jupyter.org/github/kHarshit/transfer-learning/blob/master/Transfer%20learning%20%28PyTorch%29.ipynb).*


## Project 2: dog_app.ipynb

The [notebook](https://nbviewer.jupyter.org/github/kHarshit/transfer-learning/blob/master/dog_app.ipynb) contains the project (Dog-Breed Classifier) of **Deep Learning Nanodegree** from Udacity.

The following tasks were completed:

* Detect Humans
* Detect Dogs
* Create a CNN to Classify Dog Breeds (from Scratch)
* Create a CNN to Classify Dog Breeds (using Transfer Learning)
