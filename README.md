# is this AI?
Brainstation Capstone Spring 2019 Project: is this AI?

__Abstract/Motivation:__ <br>

Professionals looking to improve their interpersonal communication skills or companies looking to help improve their transaction success rates with their customers. This capstone seeks to create a machine learning approach that's designed to identify and record any questions asked during conversation. Using NLP to analyze all text queries and return them to the user (or digital assistant) to aid them in preparing an appropriate response.

### NLP

Dataset: https://www.kaggle.com/bryanpark/the-world-english-bible-speech-dataset <br>

This dataset is composed of the following: <br>
- README.md
- wav files sampled at 12,000 KHZ
- transcript.txt. <br>

`transcript.txt` is in a tab-delimited format. <br>

The first column is the name of the `book` and audio file paths. <br> 
The second one is the `script`. <br>
The rightmost column is the `duration` of the audio file. <br>

This is a supervised learning classification problem. <br>

The goal here is to obtain the text and load it into a DataFrame and be able to parse and recognize what is a question based on a its denotation. <br>

eg. who? what? where? why? how? <br>

Going deeper, you could look at Does..? Will..? Am I..? Which is..? <br>
