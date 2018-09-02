# Keras-Applications
VGG16,VGG19,Resnet50,Inception,Xception

# Usage

Environment Setup:

1.Keras
2.Opencv2 
3.Tensorflow 
4.imutils
5.numpy
6.matplotlib

Run the following command to clone the source code from github

```bash
git clone https://github.com/Anoopparjanya/Keras-Applications
``` 
Since keras by default uses theano backend,to work on tensorflow backend run the following command:

```bash
set KERAS_BACKEND=tensorflow
```
Training

Open Anaconda prompt and set the current project dictionary and run the following command.

# VGG16

```bash
python classify_image.py --image images/tiger.jpg --model vgg16
```
The above commands will train CNN - VGG16 architecture model

![alt text](https://github.com/Anoopparjanya/Image_Classification/blob/master/Flower_prediction.png)

# VGG19

```bash
python classify_image.py --image images/tiger.jpg --model vgg19
```
The above commands will train CNN - VGG19 architecture mode

![alt text](https://github.com/Anoopparjanya/Image_Classification/blob/master/Flower_prediction.png)

# resnet50

```bash
python classify_image.py --image images/tiger.jpg --model resnet
```
The above commands will train CNN - Resnet50 architecture mode

![alt text](https://github.com/Anoopparjanya/Image_Classification/blob/master/Flower_prediction.png)

# InceptionV3

```bash
python classify_image.py --image images/tiger.jpg --model resnet
```
The above commands will train CNN - InceptionV3 architecture mode

![alt text](https://github.com/Anoopparjanya/Image_Classification/blob/master/Flower_prediction.png)

# Xception

```bash
python classify_image.py --image images/tiger.jpg --model resnet
```
The above commands will train CNN - Xception architecture mode

![alt text](https://github.com/Anoopparjanya/Image_Classification/blob/master/Flower_prediction.png)


On testing all the above architectures,xception gives the best accuracy.


# Differences between all the above applications.
