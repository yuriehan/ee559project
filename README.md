# Speech Emotion Recognition — EE559 Final Project

## Overview
Classifies emotions from speech using the RAVDESS dataset.
Models: SVM (MFCC features) and CNN (MobileNetV2 transfer learning).

## Requirements
pip install kagglehub librosa tensorflow scikit-learn matplotlib

## How to Run
1. Open `speech_emotion_final.ipynb` in Google Colab
2. Run all cells in order (Runtime → Run all)
3. The notebook will automatically download the RAVDESS dataset via kagglehub

## Results
| Model | Test Accuracy | Macro F1 |
|-------|-------------|----------|
| SVM   | 45.83%      | 0.44     |
| CNN   | 55.09%      | 0.53     |
