# Transfer Learning in PyTorch

The notebook contains the final project of **PyTorch Scholarship Challenge** from Udacity and facebook.

The 102 Category Flower [Dataset](http://www.robots.ox.ac.uk/~vgg/data/flowers/102/index.html) from Visual Geometry Group, University of Oxford, is used.

The following **steps** are described:
* Preprocessing
* Transfer learning
* Saving and loading model checkpoint
* Inference and Validation

**Analysis:**
* Model used: ResNet50
* Epochs trained: 10
* Validation accuracy: 93.64%
* Optimizer used: Adam
* Loss used: CrossEntropyLoss
* Scheduler used: StepLR
* Device used: cuda
* Comments: `fc` layer replacement with combination of linear layers with Dropout regularization 

**NOTE:** *If the notebook doesn't render here on GitHub, try it on [nbviewer](https://nbviewer.jupyter.org/github/kHarshit/transfer-learning/blob/master/Transfer%20learning%20%28PyTorch%29.ipynb).*
