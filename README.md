# Stanford-MURA

## Introduction

MURA (musculoskeletal radiographs) is a large dataset of bone X-rays. Algorithms are tasked with determining whether an X-ray study is normal or abnormal.

Musculoskeletal conditions affect more than 1.7 billion people worldwide, and are the most common cause of severe, long-term pain and disability, with 30 million emergency department visits annually and increasing. We hope that our dataset can lead to significant advances in medical imaging technologies which can diagnose at the level of experts, towards improving healthcare access in parts of the world where access to skilled radiologists is limited.

MURA is one of the largest public radiographic image datasets. We're making this dataset available to the community and hosting a competition to see if your models can perform as well as radiologists on the task.

## Folder Structure

- MURA-v1.1
  - train/
    -  Elbow/
       - Patient{id}
         - Image1
         - Image2
         - Image3
    -  Shoulder
    - ..
  - test/
    -  Elbow/
       - Patient{id}
         - Image1
         - Image2
         - Image3
    -  Shoulder
    - ..
  - csv files
  - model.ipynb
  
## Usage
- MURA.ipynb has the model
- data_preprocessing.ipynb has the EDA 

## Dependcies
- PyTorch
- Tensorflow
- Keras
- PIL
- OpenCV

## TODO
[ ] Get a GPU to train model
[ ] Add Attention
[ ] Experiment with Other Augmentations 
[ ] Add Cyclic LR
