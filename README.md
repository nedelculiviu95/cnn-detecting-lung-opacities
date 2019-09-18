## cnn-detecting-lung-opacities

Goldsmiths, University BSc Computer science final year project

## Description

This projects aims to reproduce the abnormalities lung detection deep learning model introduced in [CheXNet paper](https://arxiv.org/pdf/1711.05225.pdf) on all 14 lung diseases. Furhermore, I explored 4 new CNN architectures (DenseNet169, DenseNet201, InceptionV3 and Xception). In a nutshell, I replaced the convolutional base of CheXNet with the convolutional base of these newly CNN architectures.

The CheXNet replicated model and the newly CNN architectures were trained for 24 hours, so I could not reproduce or surpass the results reported in original paper. I just wanted to see how if these 4 architectures surpasses CheXNet.

## Results 

| Label | CheXnet | DenseNet169 | DenseNet201 | Xception | InceptionV3 |
| ----  | :-----: | :---------: | :---------: | :------: | :---------: | 
|Atelectasis | 0.777 | 0.770    |  0.756           |0.812          | 0.795            |
|Cardiomegaly | 0.903 |0.883    |  0.850           |0.901          |0.898             |
|Effusion | 0.866     |0.853    |  0.845           | 0.880         |0.874             |
|Infiltration | 0.681 |0.673    |  0.675           | 0.705         |0.685             |
|Mass | 0.776         |0.749    | 0.667            | 0.819         |0.802             |
|Nodule | 0.690       |0.652    | 0.671            | 0.762         |0.713             |
|Pneumonia | 0.725    |0.723    | 0.715            |0.761          | 0.737            |
|Pneumothorax | 0.819 |0.807    | 0.774            |0.867          | 0.833            |
|Consolidation | 0.780|0.786    | 0.766            |0.794          | 0.786            |
|Edema | 0.868        |0.870    | 0.855            |0.867          | 0.865            |
|Emphysemia | 0.840   |0.789    | 0.799            |0.907          | 0.854            |
|Fibrosis | 0.764     |0.746    | 0.716            |0.802          |0.740             |
|Pleural Thickening | 0.723 |0.719 |0.689             |0.752          |0.745             |
|Hernia | 0.772       |0.834    |0.811             |0.852          |0.842             |
|**Average AUC score**| **0.785** |**0.775** |**0.758** | **0.819**| **0.798** |
