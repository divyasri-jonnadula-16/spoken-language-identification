# spoken-language-identification
A Deep learning or/and Machine learning project
Project Overview

This project focuses on Spoken Language Identification (SLID), which automatically identifies the language spoken in an audio recording. The study compares multiple machine learning and deep learning models for classifying English, German, and Spanish speech.

Objective

The main objective is to develop and evaluate an efficient language identification system by comparing traditional machine learning, CNN-based, recurrent, and pretrained speech models.

Dataset

The dataset consists of audio recordings in:

English
German
Spanish

The experimental dataset contains 6,000 training audio samples and 540 testing samples, with 180 test samples per language.

Models Used

The following models were evaluated:

MLP Classifier
ResNet18
ECAPA-TDNN
CNN-BiLSTM
HuBERT
Wav2Vec2


Technologies Used

Python
PyTorch
Torchaudio
Librosa
Scikit-learn
NumPy
Pandas
Matplotlib
Hugging Face Transformers

Methodology

The audio data is preprocessed and converted into suitable representations for model training. Traditional models use extracted acoustic features, while deep learning models learn speech representations for language classification.
