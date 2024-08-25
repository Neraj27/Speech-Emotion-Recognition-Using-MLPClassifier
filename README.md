<h1 align="center">Speech Emotion Recognition Project</h1>
🛠 Libraries Used
librosa: Library for audio and music processing.
sklearn: Scikit-learn library for machine learning tasks.
numpy: Library for numerical computations.
pandas: Library for data manipulation and analysis.
matplotlib: Library for plotting graphs and visualizing data.
tensorflow/keras: Libraries for building and training machine learning models.
🎯 Features
Recognizes emotions from speech input.
Supports multiple emotion classes (e.g., happy, sad, angry, etc.).
Extracts key audio features such as MFCCs, chroma, and mel-spectrogram.
Trains a model using an MLPClassifier for emotion prediction.
Provides a user interface to select audio files and predict emotions.
🚀 How It Works
Feature Extraction: Uses librosa to extract relevant audio features like MFCCs from the input audio files.
Model Training: Trains an MLPClassifier on the extracted features to recognize different emotions.
Emotion Prediction: Takes an audio file as input, processes it to extract features, and uses the trained model to predict the emotion expressed in the audio.
User Interaction: Allows users to select audio files and visualize the predicted emotion.
📂 Dataset
Download Link: Link to Dataset (https://github.com/skit-ai/emotion-tts-dataset)
The dataset includes audio files labeled with emotions for training and testing the model.
