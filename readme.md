# Final Year Project

This repo contains my final year project: Deep-Learning Model For Image Enhancement

# Requirement
Python >= 3.6
Tensorflow >= 2.0

## Run
To test the model:
```
python train.py --mode=predict
```

To train the model:

You need to have a dataset before training the model, and you can download the <a href="https://drive.google.com/file/d/1dzuLCk9_gE2bFF222n3-7GVUlSVHpMYC/view">LOL-v2 dataset here</a> from Yang et al.
```
python train.py --mode=train
```

To check the model result with metrics:
```
python testresult.py --check_images_path="./Predict/Output/"
```

There are more variable can be changed, please refer to the program for infos.
