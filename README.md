# Facial-Expression-Recognition

Kaggle Facial Expression Recognintion [Challenge](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge)

## Run
* Data preprocess
```
python preprocess_fer2013.py
```
* Train and evaluate VGG19
```
python mainpro_FER.py --model VGG19 --bs 128 --lr 0.01
```
* Train and evaluate ResNet18
```
python mainpro_FER.py --model Resnet18 --bs 128 --lr 0.01
```
* Train and evaluate our combination model
```
python combine.py --bs 128 --lr 0.01
```

