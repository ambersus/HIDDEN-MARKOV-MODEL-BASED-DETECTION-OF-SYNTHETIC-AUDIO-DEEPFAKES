# HIDDEN-MARKOV-MODEL-BASED-DETECTION-OF-SYNTHETIC-AUDIO-DEEPFAKES

This project utilizes Hidden Markov Models (HMM) and Mel-Frequency Cepstral Coefficients (MFCCs) to classify audio files into two categories: "Real" and "Fake". The classification is based on the audio features extracted using MFCCs, which are then used to train an HMM model for prediction.
This project used the dataset from : https://www.kaggle.com/datasets/birdy654/deep-voice-deepfake-voice-recognition
<br><br>
The code performs the following tasks:
<br><br>
<b>Extract MFCC Features:</b> Converts audio files into a set of MFCC features that represent the spectral properties of the audio.
<br>
<b>Train an HMM Model:</b> Trains a Hidden Markov Model to classify audio as real or fake based on the extracted MFCC features.
<br>
<b>Test the Model:</b> Evaluates the trained model on unseen data and reports the classification accuracy, along with a confusion matrix.
<br>
<b>Visualize MFCCs:</b> Plots the MFCC features and the confusion matrix.
<br><br>
# How to Run
<br><br>
<b>Place Your Audio Data:<br></b>
Organize your dataset with audio files placed in two separate folders: REAL and FAKE. Each folder should contain .wav files representing 'real' and 'fake' audio recordings, respectively.
<br><br>
<b>Modify File Paths:<br></b>
In the script, update the data_folder_real and data_folder_fake variables to point to the correct locations of your audio files:
<br><br>
data_folder_real = r"C:\path\to\REAL"
<br>
data_folder_fake = r"C:\path\to\FAKE"
<br><br>
<b>Run the Code:<br></b>
After setting up your data and paths, run the script using
<br><br>
<b>Interpret the Output:<br></b>
The script will print the accuracy of the model and display a confusion matrix showing the performance of the model in distinguishing 'real' from 'fake' audio. It will also display plots of MFCC features for the test samples
