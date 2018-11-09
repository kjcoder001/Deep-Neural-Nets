# Deep-Neural-Nets
Simple neural nets implemented using tensorflow and keras

* ## MNIST CNN Using Tensorflow ##
MNIST Data is easily available on the internet. This neural net has been written in low level tensorflow code which involves running sessions. The accuracy obtained is fairly high after training 10 epochs on CPU.
* ##  MNIST Using Keras ##
This neural net uses the high level API Keras which makes prototyping deep learning models fairly easy.
* ## Facial Expression Recognition ##
The data for this network was taken from kaggle. The accuracy obtained is close to 75% on CPU which can be improved by training it longer.This notebook presents an object oriented way of building *Convolutional Neural Networks*.
* ## VGG Transfer Learning ##
Image classification using **transfer learning**. Pre-trained weights of VGG16 model trained on imagenet dataset (available in keras) were used for another task.
* ## NLP Sentiment Analysis ##
Classification of IMDB reviews as postive/negative using *Recurrent Neural Networks* (GRU more specifically).The accuracy obtained was 86% after *simplistic* hyperparameter tuning and hence can be improved further.
* ## Time Series Prediction ##
Predicted the approximate pattern of growth/decline of Google's stock price in January 2017 using past 5 years of training data.
* ## Machine Translation ##
The neural net can translate french language to english with the encoder-decoder architecture using RNNs. The data was taken from the europarl website which hosts transaltions of all the languages spoken in the european parliament.The model has not been trained yet due to lack of computational resources. The estimated time on CPU is around 60-70 hours. Will update after decent results are achieved.
* ## Attention Model ## 
The attention model is used to translate longer sequences accurately by considering the *context* of the sequence. This neural net converts various formats of human readable dates to a standard machine readable date format(YYYY-MM-DD). This notebook was a part of programming assignment in one of courses I followed(link under resources) and has been taken from there.
* ## Style Transfer ##
Extensively used in creating aesthetic pieces of art by superimposing style of one image on a general content image. The following results were obtained after training on Google cloud GPU.
![styleplusc](https://user-images.githubusercontent.com/32245327/48265400-70758000-e452-11e8-8c49-784abfcc73bf.JPG)

![venice_style](https://user-images.githubusercontent.com/32245327/48265434-8125f600-e452-11e8-9c71-3b064f58eadf.png)
## RESOURCES ##
* http://neuralnetworksanddeeplearning.com/
* https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi
* **CNN**
  * https://www.coursera.org/learn/convolutional-neural-networks
  * http://cs231n.github.io/convolutional-networks/
  * https://www.youtube.com/watch?v=vT1JzLTH4G4&list=PL3FW7Lu3i5JvHM8ljYj-zLfQRF3EO8sYv
* **RNN**
  * https://www.coursera.org/learn/nlp-sequence-models
  * https://www.youtube.com/watch?v=OQQ-W_63UgQ&list=PL3FW7Lu3i5Jsnh1rnUwq_TcylNr7EkRe6
