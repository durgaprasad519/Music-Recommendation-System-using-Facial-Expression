# Facial-Expression-Recognition
This Project is designed with the custom built dataset and it helps  in categorizing your facial expressionns into one of the categories  like 'happy', 'sad', 'neutral', 'angry' etc.

# Description
This project deals in creating an Customized dataset by our own. This dataset can be build with the help of the data collection file in which it asks about enter an expression. The user can enter the expression name and show the expression on the camera such that 100 pictures of that expression are saved in that particular expression file. Likewise different expressions are Recorded and saved as our dataset.  After the dataset was  created we are going to the Training File in which the Model is trained using the Keras library. This model is trained on different Emotions and and the you can use the Inference file to check wheter the model is predicting your expression correctly or not.

The expressions in data collection  phase are collected using the technolgies like "opencv" and "Mediapipe-Holistic".
MediaPipe is the library which takes landmarks from a particular image. Using cv the webcam  opens and closes when the user presses escape key. Holistic solutions in MediaPipe takes in the  frame and retune all the landmarks of the face. These landmarks are stored per each frame in a 
NumPy array. likewise, 100 frames are taken for each emotion like happy, surprise, sad , angry  etc.

# Note:
The Dataset Should be created by you only using the data collection code. This  is novality in this project where the user can create His/her own Dataset and train the model.
