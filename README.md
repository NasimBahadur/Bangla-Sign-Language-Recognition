# Bangla Sign Language Recognition
Bangla sign recognition system is developed based on a deep learning approach named LSTM. As a feature extractor, Mediapipe Holistic is also used in this system. This system is able to work on static and dynamic both types of gestures and recognize simple or complex signs.

# Mediapipe Holistic
Mediapipe Holistic extracts feature from a person's face, body, hand, and finger positions. Mediapipe Holistic uses specific points to monitor our facial expressions and hand movements.  Mediapipe Holistic generates landmarks to detect the face, body, and hand. As a result, redundant information is automatically removed from the picture or frame of a video. This system saves space because it only requires a few points to be saved.  t does not introduce displacement due to lighting or distance.
<p align="center">
  <img src=https://user-images.githubusercontent.com/43060004/179276570-5b054df2-84f2-4a54-8c73-9002a60b9042.jpg width="260" height="180"/>
  <img src=https://user-images.githubusercontent.com/43060004/179276576-49dd19fc-c0c3-4c27-bb5d-4dbcdb91ec2d.jpg width="260" height="180"/>
</p>
<p align="center">  
  <img src=https://user-images.githubusercontent.com/43060004/179276581-28ebf096-3b2f-433e-a6a0-6ad38df828d4.jpg width="260" height="180"/>
  <img src=https://user-images.githubusercontent.com/43060004/179276587-54089806-979b-472c-8003-b1cfc37fba73.jpg width="260" height="180"/>
</p>

# LSTM Architecture
Recurrent Neural Networks in particular may learn long-term dependencies, such as LSTM. A number of repetitive neural network modules make up RNNs. A single tanh layer, which is a very simple structure, will make up this repeating module in a normal RNN.
LSTM has backpropagation, unlike conventional convolutional neural networks. A forget gate, a cell, an input gate, and an output gate make up a basic LSTM unit. Three gates regulate the flow of data into and out of the cell, which also has a long-term storage capacity.
LSTMs do a great job of categorizing, evaluating, and generating predictions based on time series data because key events in a time series may have unexpected latency. In Bangla sign language, a complex sign consists of several patterns and gestures. A connection between recent and prior actions is nearly always present. In order to remember the previous one for a while, the LSTM architecture was used. 
<p align="center">
  <img src=https://user-images.githubusercontent.com/43060004/179276593-ccf70c0f-fbe3-4882-b1c5-46097c0960f4.png width="520" height="250"/>
  <img src=https://user-images.githubusercontent.com/43060004/179276597-c5467b13-12f5-49ea-979a-f4fcf7bc4c01.png width="520" height="250"/>
</p>
