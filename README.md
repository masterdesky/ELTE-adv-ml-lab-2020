# Advanced Machine Learning Lab 2019-2020/2 @ ELTE

## Image captioning using the MS COCO dataset
The topic of my project work on the Advanced Machine Learning course/lab was the problem of captioning images using machine learning methods, which I realized using a deep neural network architecture. During the project I used the images in the Microsoft COCO dataset and their associated captions.

The images used for teaching were preprocessed using the Inception-v3 convolutional network and then trained by using an architecture consisting of a sequence of convolutional encoders and recursive (GRU) decoders with the Bahdanau attention method implemented. I tested the predictive capabilities of the network both on the images of the original MS COCO database which were not used for teaching, and also on images I gathered from other sources.
