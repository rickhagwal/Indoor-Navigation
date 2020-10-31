# Indoor-Navigation for low vision people

•	Trained and deployed an LSTM based Deep Learning convolutional neural network on 1000 videos dataset, to classify doors and stairs in indoors, with less than 0.01% error, using Python, MobileNetv2, TensorFlow, TensorFlow Lite, Keras, Tensorboard, CNN, Google Cloud Platform (GCP), Scikit-learn, Pandas, Numpy etc.


## Demo Results-

https://www.youtube.com/watch?v=UlA3ekc-VNQ

https://www.youtube.com/watch?v=t2MwlH0lGy4&feature=youtu.be


•	Steps involved in actual implementation-


## Step 1: Building and Training model-

#### Tensorboard results-


![alt text](https://github.com/rickhagwal/Indoor-Navigation/blob/master/images/step191.PNG)

![alt text](https://github.com/rickhagwal/Indoor-Navigation/blob/master/images/step192.PNG)

## Step 2: Feature Extraction-

- Sampling the video: We don’t process every frame, we define a frame generator to create certain sequence length as 40 samples and load the dataset & specify output frames.

- Used CNN model MobileNet for feature extraction.

- Extracting Features using MobileNetv2-

![alt text](https://github.com/rickhagwal/Indoor-Navigation/blob/master/images/step24.PNG)

## Step 3: Batch Prediction-

Created MobileNetv2 Feature Extraction Model, and generated .npy file from video files-

![alt text](https://github.com/rickhagwal/Indoor-Navigation/blob/master/images/step32--.PNG)


![alt text](https://github.com/rickhagwal/Indoor-Navigation/blob/master/images/step34--.PNG)

![alt text](https://github.com/rickhagwal/Indoor-Navigation/blob/master/images/step35--.PNG)

## Step 4: Live Predictions-


![alt text](https://github.com/rickhagwal/Indoor-Navigation/blob/master/images/step48.PNG)

![alt text](https://github.com/rickhagwal/Indoor-Navigation/blob/master/images/step49.PNG)

![alt text](https://github.com/rickhagwal/Indoor-Navigation/blob/master/images/step50.PNG)

![alt text](https://github.com/rickhagwal/Indoor-Navigation/blob/master/images/step51.PNG)

![alt text](https://github.com/rickhagwal/Indoor-Navigation/blob/master/images/step52.PNG)

