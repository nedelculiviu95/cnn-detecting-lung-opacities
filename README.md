## cnn-detecting-lung-opacities

Goldsmiths, University BSc Computer science final year project

## Description

This projects aims to reproduce the abnormalities lung detection deep learning model introduced in [CheXNet paper](https://arxiv.org/pdf/1711.05225.pdf) on all 14 lung diseases. Furhermore, I explored 4 new CNN architectures (DenseNet169, DenseNet201, InceptionV3 and Xception). In a nutshell, I replaced the convolutional base of CheXNet with the convolutional base of these newly CNN architectures.

The CheXNet replicated model and the newly CNN architectures were trained for 24 hours, so I could not reproduce or surpass the results reported in original paper. I just wanted to see how if these 4 architectures surpasses CheXNet.

## Results 

| Label | CheXnet | DenseNet169 | DenseNet201 | Xception | InceptionV3 |
| ----  | :-----: | :---------: | :---------: | :------: | :---------: | 
|Atelectasis | 0.777       |             |             |          |             |
|Cardiomegaly | 0.777       |             |             |          |             |
|Effusion | 0.777       |             |             |          |             |
|Infiltration | 0.777       |             |             |          |             |
|Mass | 0.777       |             |             |          |             |
|Nodule | 0.777       |             |             |          |             |
|Pneumonia | 0.777       |             |             |          |             |
|Pneumothorax | 0.777       |             |             |          |             |
|Consolidation | 0.777       |             |             |          |             |
|Edema | 0.777       |             |             |          |             |
|Emphysemia | 0.777       |             |             |          |             |
|Fibrosis | 0.777       |             |             |          |             |
|Pleural Thickening | 0.777       |             |             |          |             |
|Hernia | 0.777       |             |             |          |             |
