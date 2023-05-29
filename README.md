# RhythmicMood
RhythmicMood is a software application that utilizes facial expression
analysis and user preferences to provide personalized song recommendations. The
system employs computer vision techniques to detect and analyze the user’s emotional state based on their facial expressions captured through a webcam. By leveraging facial landmark detection and emotion classification algorithms, the system determines the user’s emotional state, such as happiness, sadness, excitement, and more.

In addition to emotion detection, the system incorporates user preferences to further tailor the music recommendations. Users can specify their preferred language and artist choices, allowing the system to filter the recommended songs accordingly. The system utilizes relevant song metadata, including language, artist, and genre, to generate personalized recommendations that align with the
user’s emotional state and preferences.

The project involves several key components, including data collection and preprocessing of facial expression datasets, development and training of machine learning models for emotion detection, and integration of user interfaces to capture user preferences. A recommendation engine is implemented to match the user’s emotional state with suitable songs based on language, artist, and genre,
employing techniques such as collaborative filtering and content-based filtering.

## Honors project
A music based recommendation system

Python version used  : Python 3.10.2<br> 

## Install Requiremnts <br/>
``` pip install streamlit ```  <br> 
``` pip install streamlit_webrtc ``` <br> 
``` pip install opencv-python ``` <br> 
``` pip install mediapipe ```<br> 
``` pip install keras ```<br> 
``` pip install tensorflow ```<br> 

## Run the project <br> 
Inside emotion-based-music folder <br/>
``` streamlit run music.py ```<br> 
