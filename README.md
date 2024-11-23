# faceify


<div> <h1 align="center">Emotion-Driven Playlist Recommendation System 🎵</h1> </div>
INTRODUCTION

<p align="center"> <img src="static/images/emotionfy_logo.png" alt="Emotionfy Logo" width="200"/> </p>
Emotionfy is a cutting-edge system that merges the power of emotion detection with personalized music recommendations. Using deep learning for facial emotion recognition and Spotify’s API, this application recommends playlists tailored to the user’s emotional state. Upload an image, and Emotionfy will do the rest — analyzing your emotion and curating a playlist to match your mood.

TEAM MEMBERS

Rey Reyes: CNN Researcher, Backend Developer
Lucas Yao: Backend Developer, Frontend Support
Fei Lin: Frontend Developer, Backend Support
DATASETS USED

Emotion Detection FER Dataset
This dataset contains 35,887 grayscale 48x48 pixel images labeled with the following emotions:
Angry
Disgust
Fear
Happy
Neutral
Sad
Surprise
Face Expression Recognition Dataset
A complementary dataset designed for facial emotion recognition tasks.
GOAL

To enhance emotion detection by integrating Spotify's API, Emotionfy recommends playlists based on user emotions. The deep learning model analyzes facial expressions and maps them to Spotify playlists, offering a seamless blend of technology and music personalization.

MODEL ARCHITECTURE

Base Model: Pre-trained CNN fine-tuned on the FER dataset for emotion classification.
Emotion-to-Playlist Mapping: A custom layer maps detected emotions to Spotify playlists for seamless recommendations.
TECH STACK

Frontend
React: Interactive user interface
Backend
Flask: API communication and emotion detection
Spotify Web API: Playlist recommendations
Data Processing
Data augmentation and preprocessing techniques for improved model generalization
Libraries and Tools
TensorFlow and Keras: Deep learning frameworks
OpenCV: Image processing
Pandas and Numpy: Data handling
Matplotlib and Seaborn: Data visualization
Jupyter Notebook: Model development and experiments
Integration
Spotify OAuth 2.0: Secure user authentication for playlist access
Spotify Web Playback SDK: Music playback within the interface
FEATURES

Emotion Detection
Analyze facial expressions in images or real-time video streams.
Detect and classify emotions such as Happy, Sad, Angry, etc.
Playlist Recommendation
Fetch Spotify playlists tailored to the detected emotion.
Play music directly within the app.
User Interface
Upload images or stream video for real-time emotion analysis.
Display detected emotions with an accompanying playlist.
EVALUATION METRICS

Emotion Detection: Accuracy, precision, recall, F1-score
Playlist Recommendation: Relevance and alignment based on user feedback
SETUP INSTRUCTIONS

Requirements
Python 3.8 or above
Spotify Developer Account (for API integration)
