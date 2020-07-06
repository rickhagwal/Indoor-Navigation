# Indoor-Navigation for low vision people

•	Trained and deployed an LSTM based Deep Learning convolutional neural network on 1000 videos dataset, to classify doors and stairs in indoors, with less than 0.01% error, using Python, MobileNetv2, TensorFlow, TensorFlow Lite, Keras, Tensorboard, CNN, Google Cloud Platform (GCP), sklearn etc.

•	Project Layout-

http://csweb01.csueastbay.edu/~mi7383/CS663/home.html


•	Steps involved in actual implementation-


## Step 1: Building and Training model-

#### Tensorboard results-

![alt text](https://github.com/rickhagwal/Indoor-Navigation/blob/master/images/step19.PNG)

![alt text](https://github.com/rickhagwal/Indoor-Navigation/blob/master/images/step191.PNG)

![alt text](https://github.com/rickhagwal/Indoor-Navigation/blob/master/images/step192.PNG)

## Step 2: Feature Extraction-

- Sampling the video: We don’t process every frame, we define a frame generator to create certain sequence length as 40 samples and load the dataset & specify output frames.

- Used CNN model MobileNet for feature extraction.

- Extracting Features using MobileNetv2-

![alt text](https://github.com/rickhagwal/Indoor-Navigation/blob/master/images/step24.PNG)

## Step 3: Batch Prediction-

![alt text](https://github.com/rickhagwal/Indoor-Navigation/blob/master/images/step31.PNG)

![alt text](https://github.com/rickhagwal/Indoor-Navigation/blob/master/images/step32.PNG)


![alt text](https://github.com/rickhagwal/Indoor-Navigation/blob/master/images/step34.PNG)

![alt text](https://github.com/rickhagwal/Indoor-Navigation/blob/master/images/step35.PNG)

Step 4: Live Predictions-

![alt text](https://github.com/rickhagwal/Indoor-Navigation/blob/master/images/step41.PNG)

![alt text](https://github.com/rickhagwal/Indoor-Navigation/blob/master/images/step42.PNG)

![alt text](https://github.com/rickhagwal/Indoor-Navigation/blob/master/images/step43.PNG)

![alt text](https://github.com/rickhagwal/Indoor-Navigation/blob/master/images/step44.PNG)

![alt text](https://github.com/rickhagwal/Indoor-Navigation/blob/master/images/step45.PNG)

![alt text](https://github.com/rickhagwal/Indoor-Navigation/blob/master/images/step46.PNG)

![alt text](https://github.com/rickhagwal/Indoor-Navigation/blob/master/images/step47.PNG)

-Screenshots of the LiveCaptureResults:

![alt text](https://github.com/rickhagwal/Indoor-Navigation/blob/master/images/step48.PNG)

![alt text](https://github.com/rickhagwal/Indoor-Navigation/blob/master/images/step49.PNG)

![alt text](https://github.com/rickhagwal/Indoor-Navigation/blob/master/images/step50.PNG)

![alt text](https://github.com/rickhagwal/Indoor-Navigation/blob/master/images/step51.PNG)

![alt text](https://github.com/rickhagwal/Indoor-Navigation/blob/master/images/step52.PNG)

