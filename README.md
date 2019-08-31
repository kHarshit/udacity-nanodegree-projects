# pytorch-projects

The notebooks contain the projects of **PyTorch Scholarship Challenge** and **Deep Learning Nanodegree** from Udacity and facebook.

## Project 1: Flower image classification

The [flower_image_classification.ipynb](https://nbviewer.jupyter.org/github/kHarshit/pytorch-projects/blob/master/flower_image_classification.ipynb) contains the project Flower image classifier.
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


## Project 2: Dog breed classification

The [dog_breed_classification.ipynb](https://nbviewer.jupyter.org/github/kHarshit/pytorch-projects/blob/master/dog_breed_classification.ipynb) contains the project Dog-Breed Classifier.

The following tasks were completed:

* Detect Humans
* Detect Dogs
* Create a CNN to Classify Dog Breeds (from Scratch)
* Create a CNN to Classify Dog Breeds (using Transfer Learning)


## Project 3: TV Script generation

The [tv_script_generation.ipynb](https://nbviewer.jupyter.org/github/kHarshit/pytorch-projects/blob/master/tv_script_generation.ipynb) contains the project TV Script generation.

* The project uses LSTM.


## Project 4: Face Generation using DCGAN

The [face_generation_dcgan.ipynb](https://nbviewer.jupyter.org/github/kHarshit/pytorch-projects/blob/master/face_generation_dcgan.ipynb) contains the project on face generation.

* Model used: DCGAN (Deep Convolutional Generative Adversarial Networks)
  * Discriminator: strided convolution > batch norm > leaky ReLU
  * Generator: transpose convolution > batch norm > ReLU
* Optimizers: Adam
* learning rate: 0.0002
* beta1 = 0.5  *(changed from 0.9)*
* beta2 = 0.999  *(default value)*


## Project 5: Deploying sentiment analysis model on Sagemaker

The [sagemaker_sentiment_analysis.ipynb](https://nbviewer.jupyter.org/github/kHarshit/pytorch-projects/blob/master/sagemaker_sentiment_analysis.ipynb) contains the project Deploying sentiment analysis model in PyTorch on [AWS](https://aws.amazon.com/) using Amazon Sagemaker.


* Download or otherwise retrieve the data.
* Process / Prepare the data.
* Upload the processed data to S3.
* Train a chosen model.
* Test the trained model (typically using a batch transform job).
* Deploy the trained model.
* Use the deployed model for web app.
    * Setting up a Lambda function.
    * Setting up API Gateway.


## Project 6: Neural Style Transfer

The [project](https://github.com/kHarshit/style-transfer) implements Image Style Transfer Using Convolutional Neural Networks following an implementation by *Leon A. Gatys et al*.
