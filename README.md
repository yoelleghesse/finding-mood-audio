This script takes an audio file (chile.wav) as input, transcribes the speech using Google's speech recognition API, and performs sentiment analysis on the transcribed text. It determines whether the speech is positive or negative based on the compound sentiment score provided by NLTK's Vader sentiment analysis tool.

Install dependencies:

``pip install SpeechRecognition nltk``

Download NLTK data:

``import nltk
nltk.download('vader_lexicon')``

Ensure that the audio file (chile.wav) you want to analyze is placed in the project folder.

Execute the Python script to perform sentiment analysis on the speech data:

``python speech_sentiment_analysis.py``

The script will print out the sentiment analysis results, indicating whether the speech is positive or negative.
