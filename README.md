## CS_T02828_HW1: Stanford cars classification
*Student ID: 309553007*

### Hardware
* Python 3.7
* Pytorch

### Reproducing Submission
To reproduct my submission without retrainig, do the following steps:
1. Dataset Preparation
2. Download Pretrained models
3. Inference

### Dataset Preparation
Traning and Testing images need to be placed in different folders according to the classes
```
CS_T0828_HW1
    +- train
    |  +- AM General Hummer SUV 2000
    |  +- Acura RL Sedan 2012
    |  ...
    |  ...
    +- test
    | +- AM General Hummer SUV 2000
    | +- Acura RL Sedan 2012
    | ...
    | ...
```
### Download Pretrained models
Download pretrained models from model folder

### Training
Use Resnet50 as my training model

### Inference
To inference all models, simply run ```CS_T0828_HW1.ipynb``` from **Start inference**
