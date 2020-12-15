# GANDroid

## Introduction
* There are many black box detectors which are mostly based on Machine Learning. As a matter of fact, they have improved the security against malware attacks reasonably. But are they perfect?
* This work shows that the black box anti-virus softwares are not reliable and can be broken down by using the same Machine Learning techniques.
* This methodology involves training a General Adversial Network to produce malware samples that convinces the Black Box Detectors that they are benign.
* There are some similar works done in this area, and this work is an extension of them. But most importantly, this method is used to produce malware samples that could be injected into android apps, and make them appear benign. As most of the malware is now being shared and replicated through apps, this is consdered to be severely important.

## References:
The work is inspired from and an extension to the pioneer paper MALGAN by
Hu, Weiwei & Tan, Ying. (2017). Generating Adversarial Malware Examples for Black-Box Attacks Based on GAN. 

The dataset is obtained from 
Mahindru, Arvind (2020), “Android permissions dataset, Android Malware and benign Application Data set (consist of permissions and API calls)”, Mendeley Data, V3, doi: 10.17632/b4mxg7ydb7.3

## Execution
**** Additional research needs to be done hence kept the code encrypted in GANDroid.zip
The dataset after preprocessing is made available 
The Zip consists of 2 csv files for each of the malware and benign binary encoded datasets.
The Data preprocessing code is also made available which was implemeted initially to retrieve instances and features from the raw dataset. 
The execution requires Tensorflow, Keras and Scikit Learn dependencies.
****

