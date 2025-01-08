# Identifing snoring sounds
## By Aditya Pendyala

## Project Description

This project focuses on analyzing a dataset of snoring audio files to build machine learning models that can classify and predict various snoring patterns. It involves data preprocessing, feature extraction from audio, and model building to make predictions based on the audio features.

## Project Objectives

- Preprocess and clean raw snoring audio data.
- Extract key features from audio files.
- Train machine learning models to classify snoring sounds.
- Evaluate model performance and improve accuracy.
- Provide an easy-to-use pipeline for further snoring audio analysis.

## Folder Structure
SnoringDetection/
│
├── data/
│   └── Snoring_Dataset/
│       ├── 0/
│       ├── 1/
│       ├── Images/
│       │   └── mel_spectrogram/
│       │       ├── train/
│       │       └── val/
│       ├── mel_spectrogram_vgg16_model.h5
│       └── Snoring_dataset.txt
│
├── notebooks/
│   ├── final_Notebook.ipynb
│   └── Notebook.ipynb
│
├── reports/
│   ├── README.md
│   ├── report.docx
│   ├── report.pdf
│   └── Report1.pdf
│
├── results/
│   ├── examples.png
│   ├── README.md
│   ├── sgd_result.png
│   └── vgg16_result.png
│
├── .gitattributes
├── .gitignore
└── README.md



## Setup Instructions

### 1. Clone the repository

To get started, clone this repository to your local machine:

git clone https://github.com/pendyal1/cmse492_project.git
cd cmse492_project

### 2. Installing dependencies
The following Python libraries are required for this project:

- Pandas: Data manipulation and analysis (pandas)
- NumPy: Numerical computing with arrays (numpy)
- Matplotlib: Plotting library for visualizations (matplotlib)
- Seaborn: Statistical data visualization (seaborn)
- Scikit-learn: Machine learning library (scikit-learn)
- Includes LinearRegression, train_test_split, and r2_score
- Librosa: Audio analysis library for extracting features from audio files (librosa)
- Scipy: Scientific computing library, used here for skew and kurtosis functions (scipy)
- Wave: Module for reading and writing .wav files (wave)

you can install the dependencies using this command:
pip install pandas numpy matplotlib seaborn scikit-learn librosa scipy


