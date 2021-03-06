# EXPLORING AUDIO ONSET DETECTION WITH DEEP LEARNING 

This work aims to further explore the task of Audio On-set Detection with deep learning, presenting a novel Convolutional  Recurrent  Neural  Network  model  for  musicalonset  detection.  In  particular,  the  proposed  architecturehas been trained with different hyper-parameter tuning andCNN kernel filters size in order to find the best combina-tion of parameters in terms of performances. Two differentdataset have been used for the scope of the project, *Leveau* dataset [1] and the merge of it with *Holzapfel* dataset [2].The model has been been trained with two different input, spectrogram  and log-normalized  Mel  Band  spectrogram. 

[1]: http://www.tsi.telecom-paristech.fr/aao/en/2011/07/13/onset_leveau-a-database-for-onset-detection/
[2]
> André Holzapfel, Yannis Stylianou, Ali C Gedik, andBarı ̧s Bozkurt. Three dimensions of pitched instrumentonset detection.IEEE Transactions on Audio, Speech,and Language Processing, 18(6):1517–1527, 2009


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 

### Prerequisites

The following modules are necessary to run the notebook: numpy, essentia, sklearn, matplotlib and seaborn.

All the modules will be directly imported running the notebook.

Essentia will be installed directly running the notebook.

### Dataset 

You can download the *Leveau* dataset from this link: http://www.tsi.telecom-paristech.fr/aao/en/2011/07/13/onset_leveau-a-database-for-onset-detection/

Plase, contact the authors of the paper [2] to download the *Holzapfel* dataset. 

## Open the notebok in Google Colab

The notebook can be directly open from Google Colab: 

#### LH_LogMel
Dataset used: Leveau + Holzapfel
Input Features: Log normalized Mel Band spectrogram 

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/RonFrancesca/MIR-Audio-Onset-Detection-CRNN/blob/master/MIRProject_LH_LogMel.ipynb)

#### LH_Spectrogram 
Dataset used: Leveau + Holzapfel
Input Features: spectrogram  

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/RonFrancesca/MIR-Audio-Onset-Detection-CRNN/blob/master/MIRProject_LH_Spectrogram.ipynb)

#### Leveau_LogMel
Dataset used: Leveau
Input Features: Log normalized Mel Band spectrogram 

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/RonFrancesca/MIR-Audio-Onset-Detection-CRNN/blob/master/MIRProject_Leveau_LogMel.ipynb)

#### Leveau_spectrogram
Dataset used: Leveau
Input Features: spectrogram 

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/RonFrancesca/MIR-Audio-Onset-Detection-CRNN/blob/master/MIRProject_Leveau_spectrogram.ipynb)

Read the Notebook instructions to properly change directories paths and run the notebook correctly.

All the data used in this work have been stored in Goodle Drive, so they can be mount directly from the notebook. 
Change the path if you have the data saved on you local machine or some other clouds. 


## Clone or Download the repository 

If the user wants a local copy of the notebook, clone or download the reposiotry.
It contains a Google Colab notebook, please read the Notebook instruction to properly change directories paths and run the notebook correctly.

Command to clone the repository:
```
$ git clone https://github.com/RonFrancesca/MIR-Audio-Onset-Detection-CRNN.git
```
Once the notebook is installed, open it from google colab and follow the instruction to configure it correctly. 


## Author 
- Francesca Ronchini
