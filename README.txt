CAPTCHA Breaker
Explanation:
In this project, firts each CAPTCHA picture is splited into 5 pictures that contain letters of captcha.Then extracted letters are used for trainig model.
For neural network model, a convolutional network with 2 Convolutional layer with a Maxpooling layer after each and 2 Dense layer at the end is used. 
For predicting part, letters of CAPTCHA is predicted seprately and is combined at end to compare with actual sequence.

Results:
After running this code, it wil start training CNN model that will take few minutes. After training, model will be saved as CAPTCHABreaker.h5 file. At the end, Accuracy percentage of predicted values will be printed and also be written in result.txt file. Also diagrams of loss and accuracy values in train process will be saved as history_loss.png and history_accuracy.png files.
sample result files can be finde in Results folder.

How to Run:
Dataset zip file should be in same directory as CAPTCHABreaker.py file.

You can run the script with command bellow:

python CAPTCHABreaker.py
