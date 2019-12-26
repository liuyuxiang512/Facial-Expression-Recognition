# Facial-Expression-Recognition

Kaggle Facial Expression Recognintion Challenge

## Run
Download [Facial Expression Recognition Dataset](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge)

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

Refer to [project](https://github.com/liuyuxiang512/CS420-Bonus) for subsequent adversarial machine learning based on this project.
