# RNN and LSTM for hand rocking motion detection

Wearable sensors have been shown to be effective for promoting self awareness, wellness and re education. For this project, you will develop a detector for Body5rocking behavior from a blind subject (also commonly observed in individuals with autism) using inertial measurements from a wearable system. Two sensors, one of the wrist and another on the arm (as illustrated on the right), were used to record motion using accelerometers and gyroscopes. The data will consists of sessions about 152 hours long each with annotations of when the behavior was observed. Your goal will be to train a classifier for the detections of these events. This project will have two parts: In the first phase, you are welcome to try any machine learning approach for detection (e.g., Random Forest, SVM, MLP, etc). This will serve as your baseline for the second part of the project. We will provide you a test set for which you will turn in predictions in a format to be specified soon. The results from all the teams will be shared to the class in order to give you an idea of what to expect for performance. For the second phase, you will be expected to implement a recurring neural network (e.g., LSTM or CNN5LSTM) for learning features from the data and improving on your results from the first part of this project. 


## Part 1

Implemented manual extraction of features and logistic regression model on the resulting data.

## Part 2

Implemented CNN-LSTM to automatically extract features from the data.