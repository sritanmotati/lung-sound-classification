# Diagnosing Pulmonary Diseases from Recordings of Respiratory Cycles

The main.ipynb file contains the code used for the creation of this machine learning model. We used a convolutional neural network trained on images displaying various features of the audio file such as spectrograms and chromograms. These images were produced from the audio files using [librosa](https://librosa.org/). The database we used was the [Respiratory Sound Database](https://www.kaggle.com/vbookshelf/respiratory-sound-database) on Kaggle. Read the paper for this database [here](https://eden.dei.uc.pt/~ruipedro/publications/Conferences/ICBHI2017a.pdf).

The machine learning model we created was able to distingiush between the respiratory sounds of chronic obstructive pulmonary disease (COPD), upper respiratory tract infections (URTI), bronchiectasis, pneumonia, bronchiolitis, and healthy patients. After training the model several times, we achieved an average accuracy of 97%, with a low of 95% and a high of 99%.

A portion of the code is adapted from [here](https://www.kaggle.com/markdenton/cnn-disease-classification-linked-features-95).
