This project records an audio sample and predicts emotions using MFCC feature extraction.

Features:
 Records a short audio clip
 Extracts MFCC (Mel-Frequency Cepstral Coefficients) features
 Predicts emotions (Happy, Sad, or Neutral) based on MFCC analysis

Requirements:
 Ensure you have Python installed and install the necessary dependencies:
 pip install numpy librosa sounddevice wavio
 How to Run

Run the script:
 python speech_emotion_recognition.py
 Speak into the microphone during recording.
 The script will analyze the audio and print the predicted emotion.

Next Steps:
 Improve emotion classification with a Machine Learning model.
 Train on real datasets like RAVDESS, CREMA-D, or TESS.
 Integrate with a deep learning framework like TensorFlow or PyTorch.
