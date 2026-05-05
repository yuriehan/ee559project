# Speech Emotion Recognition — EE559

## Overview
Classifies emotions from speech using the RAVDESS dataset.
Models: SVM (MFCC features) and CNN (MobileNetV2 transfer learning).

## Requirements
pip install kagglehub librosa tensorflow scikit-learn matplotlib

## How to Run
**Option 1 — Google Colab (recommended):**
1. Open `speech_emotion_final.ipynb` in Google Colab
2. Run all cells in order (Runtime → Run all)
3. The notebook will automatically download the RAVDESS dataset via kagglehub

**Option 2 — Python script:**
1. Install the required packages above
2. Run `python speech_emotion_final.py`
3. The script will automatically download the RAVDESS dataset via kagglehub

## Results
| Model | Test Accuracy | Macro F1 |
|-------|-------------|----------|
| SVM   | 45.83%      | 0.44     |
| CNN   | 55.09%      | 0.53     |
