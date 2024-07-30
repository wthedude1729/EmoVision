# EmoVision: Multimodal Emotion Recognition
This project aims to recognize emotions for various different modalities, such as text, audio, and videos. We use several different models, which will be detailed in the next few sections. 

## Audio
Here, we take audio files from the RAVDESS dataset. We convert the audio files to spectrograms using librosa's STFT function. We use a ResNet-18 model and train it on this dataset.

## Text
We took Twitter tweets from the Sentiment-140 dataset. This dataset was then plugged in to a Bi-LSTM for classification. 

## Videos
We split videos from the Ekman-6 dataset into frames, audio, and text. We then plugged this into our novel architecture for emotion recognition. 
