# HIDDEN-MARKOV-MODEL-BASED-DETECTION-OF-SYNTHETIC-AUDIO-DEEPFAKES

This project utilizes Hidden Markov Models (HMM) and Mel-Frequency Cepstral Coefficients (MFCCs) to classify audio files into two categories: "Real" and "Fake". The classification is based on the audio features extracted using MFCCs, which are then used to train an HMM model for prediction.
<br>
The code performs the following tasks:
<br>
Extract MFCC Features: Converts audio files into a set of MFCC features that represent the spectral properties of the audio.
<br>
Train an HMM Model: Trains a Hidden Markov Model to classify audio as real or fake based on the extracted MFCC features.
<br>
Test the Model: Evaluates the trained model on unseen data and reports the classification accuracy, along with a confusion matrix.
<br>
Visualize MFCCs: Plots the MFCC features and the confusion matrix.
<br><br>
How to Run
<br>
Place Your Audio Data:<br>
Organize your dataset with audio files placed in two separate folders: REAL and FAKE. Each folder should contain .wav files representing 'real' and 'fake' audio recordings, respectively.
<br>
Modify File Paths:<br>
In the script, update the data_folder_real and data_folder_fake variables to point to the correct locations of your audio files:
<br>
data_folder_real = r"C:\path\to\REAL"
<br>
data_folder_fake = r"C:\path\to\FAKE"
<br>
Run the Code:<br>
After setting up your data and paths, run the script using
<br>
Interpret the Output:<br>
The script will print the accuracy of the model and display a confusion matrix showing the performance of the model in distinguishing 'real' from 'fake' audio. It will also display plots of MFCC features for the test samples
