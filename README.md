# EmotionPrediction
A machine learning problem that takes as an input a Frozen or StarWars audio segments and predicts the emotions(happy or neutral) present in the audio signals.
The interesting  thing about it is the features extracted from the audio signals of Frozen and StarWars audio signals and modelling the features through MLP classifier to predict the emotions(happy or neutral).
Predicting emotions would be useful in many areas like call centre to predict the emotion of their customers and greet them accordingly.

Machine Learning pipeline**

**Input :** 
For the input we have taken "Humming or Whistling" Starwars or Frozen audio files.

**Output:** 
For the output we would be gettting "Happy" or "Neutral" emotions

**Intermediate Stages:**
1. Environment Setup: Loading the required libraries and accessing to drive
2. Data Accessing from Drive
3. Exploratory Data Analysis
Finding the number of files in the google drive "Mini_Project" folder.
Displaying the various(5) audio files
Getting the name of the audio files
4. Extracted Features:
MFCC (mfcc)
Chroma (chroma)
MEL Spectrogram Frequency (mel)
5. Building training and testing data
6. Modelling 
7. Finding Accuracy
8. Displaying the Classification Report
9. Displaying the confusion matrix

