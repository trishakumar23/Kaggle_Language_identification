# Kaggle_Language_identification

## Introduction

Introduction Language Identification (LID) systems from voice are classification models that predict the spoken language from a given audio recording. The LID systems can facilitate the process of any speech processing system such as speech recognition (ASR) or speech translation systems. In speech-based assistant systems, LID works as a first step by selecting the appropriate grammar from a list of available languages for further semantic analysis. Also, these models can be employed in call centers in order to redirect an international user to an operator who is fluent in that identified language.

Objective The objective of this project is to use machine learning methods for constructing a LID model which can discriminate 4 languages; English, French, Arabic, Japanese. There are 2 expected phases. The first phase is constructing a classifier. It is expected to compare the performance of different models, optimize the hyperparameters, and practice of finding the best model. The second phase is the evaluation of the model in a simulated situation of real life deployment. The objective is to understand the challenge of generalization. It's also expected to analyze the result of the model’s performance and make hypothesis about the weak and strong aspect of models. The competition among models' accuracy can provide a better understanding of performance

Data The provided dataset has been collected from TEDx talks YouTube for the Language Identification task from audio. The samples are recorded audio of speaker speech from available TEDx talks videos. In order to have a standard sample's type, they follow below convention. The length of recorded audio files should be around 5 seconds (5.00 - 5.99 seconds). The format of audio files should be *.wav. The sample rate of recording files should be 16 kHz (in mono format).

Dataset A repository contains recording files in the standard format (.wav, 16kHz, mono, 5-6 seconds) and a .txt file with 4 information (separated by , ) for each recorded file (one file per line) has been provided. The 1st column is the name of *.wav file The 2nd column is the URL address of YouTube video The 3rd column is the starting time of recording from YouTube video The 4th column is the label (language) of recorded speech (EN, FR, AR, JP)

Evaluation set A repository contains recording files in the standard format (.wav, 16kHz, mono, 5-6 seconds) and a .txt file with 2 columns as the file names and a the predicted label by your classification model.


## Acknowledgments:

Tutor : Manel Rebhi 

Team Members : Gael Cavecchia, Nathan Destrez, Trisha Kumar
