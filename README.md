# capstone
Brainstation Capstone Spring 2019 Project: is this AI?

Abstract/Motivation: 

Professionals looking to improve their interpersonal communication skills or companies looking to help improve their transaction success rates with their customers. This capstone seeks to create a machine learning approach that's designed to identify and record any questions asked during conversation. Using NLP to analyze all text queries and return them to the user (or digital assistant) to aid them in preparing an appropriate response.

NLP
Dataset: https://www.kaggle.com/bryanpark/the-world-english-bible-speech-dataset 

This dataset is composed of the following: 

README.md
wav files sampled at 12,000 KHZ
transcript.txt.
transcript.txt is in a tab-delimited format. 

The first column is the name of the book and audio file paths. 
The second one is the script. 
The rightmost column is the duration of the audio file. 

This is a supervised learning classification problem. 

The goal here is to obtain the text and load it into a DataFrame and be able to parse and recognize what is a question based on a its denotation. 

eg. who? what? where? why? how? 

Going deeper, you could look at Does..? Will..? Am I..? Which is..? 
