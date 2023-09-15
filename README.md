# Speech_Emotion_Detection
Speech Emotion Detection using Keras 

My first step was to select a dataset, I browsed on Kaggle and found many datasets related to speech emotion detection, out of them I chose the Toronto emotional speech set as it had the relevant data required.
I extracted data only regarding happy, sad, angry, and neutral emotions.
The libraries I primarily used were Keras,librosa, pandas, and matplotlib.
After loading the data, by using different graphs I was able to differentiate between what the different emotion's features looked like.
The next step was to select the type of model to be trained. I chose a Sequential Model as it seemed like the best approach. For feature extraction, I used MFCC and applied it to the training and testing data.
After training the model, I applied it to my test set, and based on the results you can see that there is a significant amount of inaccuracies.
The main challenge I faced was to finetune the model and the data to reduce the number of wrong predictions. 
After analyzing it a bit the model mainly misinterprets the difference between sad and neutral and neutral and angry.

