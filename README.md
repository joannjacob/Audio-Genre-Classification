# Audio-Genre-Classification

Classify audio file into genres using deep learning techniques

This project is done as part of DS 5500 - Capstone Project 
Group 8: Anurathi Bala, Joann Rachel Jacob & Mitchell Leahy

Audio genre classification is essential for various music ap-
plications, including recommendation systems and content
organization. This project investigates the efficacy of differ-
ent deep learning architectures, namely Convolutional Neural
Networks (CNNs), Long Short-Term Memory (LSTM) net-
works, and Vision Transformers (VIT), for audio genre clas-
sification. The study utilizes the GTZAN and FMA Small
datasets, offering a diverse collection of audio tracks span-
ning multiple genres.
To perform genre classification, acoustic features such as
MFCC and Mel Spectrograms are extracted from the audio
files in the GTZAN and FMA Small datasets. These features
serve as the foundation for training and evaluating novel ar-
chitectures, including Vision Transformer, RNN-LSTM, and
CNN-based models. Extensive experimentation is conducted,
and performance evaluation metrics, including accuracy, pre-
cision, recall, and F1 score, are employed. The CNN and VIT
models leverage spatial information present in the spectro-
grams, while the LSTM model effectively captures temporal
dependencies in the MFCC sequences. Experimental results
demonstrate that the LSTM model performs well, achieving –
accuracy using MFCCs, while the CNN model achieves – ac-
curacy using Mel Spectrograms. However, the Vision Trans-
former model exhibits lower accuracy and requires further
improvement.
Through a comparative analysis of these architectures, con-
sidering their strengths and weaknesses, this project con-
tributes to the understanding of deep learning-based audio
genre classification and provides insights for future advance-
ments in this field.


## Table of contents
* [Datasets](#datasets)
* [Libraries and Tools](#libraries)
* [Models](#models)
* [Notebooks](#notebooks)

# Datasets
  - GTZAN Dataset - https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification
  - FMA Small Dataset - https://www.kaggle.com/datasets/imsparsh/fma-free-music-archive-small-medium

GTZAN Dataset
1. Download the GTZAN dataset from https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification 
2. Upload it into your drive. (Create a folder and upload the folder downloaded here. It should have the folder name "Data" which contains images_original, genres_original, features_3_sec.csv and features_30s.csv)
3. Use the correct link to your drive in the required cells.
   
FMA Dataset
1. Original FMA Dataset GitHub repository - https://github.com/mdeff/fma. Downloading the data from the original repo and loading it into the drive takes a long time and space since it is 7.2 GB, so instead we are using the FMA Small from Kaggle using Kaggle API
FMA Kaggle Dataset - https://www.kaggle.com/datasets/imsparsh/fma-free-music-archive-small-medium
2. Download your Kaggle API file kaggle.json and upload into the colab by running the cells in the notebook. This is needed to download the dataset into the notebook.

## Libraries and Tools
* Python 
* TensorFlow
* Keras
* Pandas
* NumPy
* Matplotlib
* Libroasa

## Models

* CNN
* LSTM
* Vision Transformer (ViT)

## Notebooks

* Preprocessing and EDA of GTZAN dataset
* CNN GTZAN.ipynb
* CNN FMA.ipynb
* VIT GTZAN.ipynb
* VIT FMA.ipynb
* LSTM GTZAN.ipynb


