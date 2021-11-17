# EE603-Machine-Learning-Signal-Processing
## Model Codes
Model Codes can be found in the `FinalModelCodes` folder. To run the training and generate the same results, all the codecells can run in order, after creating a shortcut to our dataset in your drive and passing the path to the dataset.

1. [CNN](FinalModelCodes/CNN_FINAL.ipynb)
2. [RNN](FinalModelCodes/RNN_FINAL.ipynb)
3. [DNN](FinalModelCodes/DNN_FINAL.ipynb)
4. [Logistic Regression](FinalModelCodes/LogReg_final.ipynb)
5. [Template Matching](FinalModelCodes/TemplateMatching_final.ipynb)
6. [GMM](FinalModelCodes/GMM_final.ipynb)
## Report
Project Report can be found [Project Report.pdf](ProjectReport.pdf)

## Weights
Weights can be found in the `weights` folder.

## Dataset
Dataset can be found [here](https://drive.google.com/drive/folders/1u7Oh_hp28TusSOafFaI8QMfUjjfrKQkf?usp=sharing) and [here](https://drive.google.com/drive/folders/1SWQSspPaCj0_u0O6cLLyB_ijogPIfoBA?usp=sharing).


## Directory Structure
```
EE603-Machine-Learning-Signal-Processing
│   Decoding.ipynb
│   FeatureComparision.ipynb
│   LICENSE
│   Project Report.pdf
│   README.md
│
├───DatasetPipeline
│       DatasetGeneration_FINAL.ipynb
│       Generate_Test_Data.ipynb
│
├───FinalModelCodes
│       CNN_FINAL.ipynb
│       DNN_FINAL.ipynb
│       GMM_final.ipynb
│       LogReg_final.ipynb
│       RNN_FINAL.ipynb
│       TemplateMatching_final.ipynb
│
├───OldTestCodes
│       ClassifierOldMFCCVariant.ipynb
│       DatasetGeneration.ipynb
│       GMM.ipynb
│       LogReg.ipynb
│
└───weights
    │   gmm_weights.npy
    │   logRegWeights.zip
    │
    ├───CNN_FINAL_MFCC_CORRECT
    │   │   keras_metadata.pb
    │   │   saved_model.pb
    │   │
    │   └───variables
    │           variables.data-00000-of-00001
    │           variables.index
    │
    ├───DNN_FINAL_MFCC_CORRECT
    │   │   keras_metadata.pb
    │   │   saved_model.pb
    │   │
    │   └───variables
    │           variables.data-00000-of-00001
    │           variables.index
    │
    └───RNN_FINAL_MFCC_CORRECT
        │   keras_metadata.pb
        │   saved_model.pb
        │
        └───variables
                variables.data-00000-of-00001
                variables.index
```