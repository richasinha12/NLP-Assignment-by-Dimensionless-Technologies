Task 1:
For task 1   I have used open-sourced Automatic Speech Recognition (ASR) models such as Wav2Vec. Dependencies:
transformers
torchaudio
torch

Task 2:
For task 2 I have built simple RandomForestClassifier model as the classifier and train it using the features and labels obtained after preprocessing training data and feature extraction(Used CountVectorizer for feature extraction). To include entity recognition in the NLU model I've used spaCy library

Task 3:
In task 3 I have separated the sentences based on period and then applied the trained model and saved the result in specified json fromat.

Task 4:
In task I have created the summary report that contains sentence and entities count.
