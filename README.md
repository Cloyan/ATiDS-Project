# ATiDS-Project
**Project Description:**
In this project, we seek to build a model that is proficient in distinguishing between grayscale images of stars and galaxies. We seek to accomplish this by acquiring a dataset from Kaggle and then applying some basic augmentation techniques before feeding the resulting dataset for training to existing models as well as experimental models we create from those models.  
**Repository and code structure:**
This repository contains the following: this README file and an ipynb file containing the code of this project. The code is in Python and has the following structure:  
- Preparing data and importing and installing necessary packages
- Data preprocessing and metrics
- Model Implementation
  - Base Models
  - Experimental Models
- Model Training
  - Base Models
  - Experimental Models
- Model Evaluation
  - Base Models
  - Experimental Models

**Executing the code:**
To run the notebook in commandline, first install "runipy" with  
<br />
pip install runipy  
<br />
Then go to the directory of the notebook and run with the following  
<br />
runipy Code.ipynb  
<br />
**Results:**
The following are the test accuracies for all the models ranked from worst to best:  
AlexNet with dropout and batch normalization: 0.692  
GoogLeNet with untrainable ImageNet weights: 0.734  
GoogLeNet: 0.746  
AlexNet with batch normalization: 0.767  
LeNet-5 skeleton: 0.767  
AlexNet with dropout: 0.768  
LeNet-5 with batch normalization: 0.771  
LeNet-5 with dropout: 0.771  
LeNet-5 with dropout and batch normalization: 0.771  
GoogLeNet with trainable ImageNet weights: 0.776  
AlexNet skeleton: 0.781  
ResNet-50 with ImageNet weights and fine-tuning: 0.788  
ResNet-50: 0.861  
