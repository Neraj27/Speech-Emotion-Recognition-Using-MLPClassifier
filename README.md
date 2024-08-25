<h1 align="center">Speech Emotion Recognition Project</h1>

## 🛠 Libraries Used
- **librosa**: Library for audio and music processing.
- **sklearn**: Scikit-learn library for machine learning tasks.
- **numpy**: Library for numerical computations.
- **pandas**: Library for data manipulation and analysis.
- **tensorflow/keras**: Libraries for building and training machine learning models.
  
## 🎯 Features
- Recognizes emotions from speech input.
- Supports multiple emotion classes (e.g., happy, sad, angry, etc.).
- Extracts key audio features such as MFCCs, chroma, and mel-spectrogram.
- Trains a model using an MLPClassifier for emotion prediction.
- Provides a user interface to select audio files and predict emotions.

## 🚀 How It Works
1.**Feature Extraction**: Uses librosa to extract relevant audio features like MFCCs from the input audio files.
2.**Model Training**: Trains an MLPClassifier on the extracted features to recognize different emotions.
3.**Emotion Prediction**: Takes an audio file as input, processes it to extract features, and uses the trained model to predict the emotion expressed in the audio.
4.**User Interaction**: Allows users to select audio files and predicted emotion.

## 📂 Dataset
- **Download Link**: Link to Dataset (https://github.com/skit-ai/emotion-tts-dataset)
- The dataset includes audio files labeled with emotions for training and testing the model.

  ## 📈 Model Performance
- The trained MLPClassifier achieves an accuracy rate of **72.40%** in predicting emotions from speech data.
