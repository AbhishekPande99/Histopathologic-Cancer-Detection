# Histopathologic-Cancer-Detection
It was a kaggle based competition in which an algorithm was to be created to identify metastatic cancer in small image patches taken from larger digital pathology scans. The data for this competition is a slightly modified version of the PatchCamelyon (PCam) benchmark dataset (the original PCam dataset contains duplicate images due to its probabilistic sampling.

## How to proceed?
Firstly we need to preprocess the data. I used image augmentation techniques(imgaug). Processing such as random cropping, adding gaussian noise, blurs etc.<br/>
I used pre trained models of NASNet and Resnet available in keras.application. For using inception v4, I used the keras code of inception v4 and then used it by excluding the top.<br/>
