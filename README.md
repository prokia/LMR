####  Introduction
Source code for Geometric-aware deep learning enables discovery of natural product-based liposomes for tumor targeting therapy.


####  Environments
LMR requires anaconda with python 3.7 or later, cudatoolkit=11.1 and below packages
```
torch                     1.7.1+cu110
torch-cluster             1.5.9
torch-geometric           1.6.3
torch-scatter             2.0.7
torch-sparse              0.6.10
torch-spline-conv         1.2.1
torchvision               0.8.2+cu110
```

LMR has been tested on Ubuntu 18.04, with eight GPUs (Nvidia RTX4090). Installation should take no longer than 20 minutes on a modern server.

#### Data
GLUT1 dataset originally consists of 14231 molecules collected from CHEMBL and LMR dataset consists of 166 molecules from literature.

####  For pre-training
Check the following scripts:
```
pretrain.py
```


####  For downstream task
Check the following scripts:

```
finetune_classification.sh
```
