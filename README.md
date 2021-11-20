# YOLACT_training
Use YOLACT training instance segmentation, the training set data is downloaded from [roboflow Raccoon Dataset](https://public.roboflow.com/object-detection/raccoon) and then labeled.

The labeled data is placed in the raccoon_dataset folder.

## Create dataset
Before training, first convert the training data into COCO format. 

Execute create_dataset.ipynb to convert the training data format.

## Training
Execute training.ipynb for training. 

## raccoon instance segmentation model
The trained model is placed in [weights](https://drive.google.com/file/d/1-krXfUVDmpv2SFyJBz2aDL537xSLlmuY/view?usp=sharing)

## Predict result
The predicted results are as follows
![image]()

## Flow
The detailed process can refer to my Medium: [YOLACT 訓練教學](https://medium.com/ching-i/yolact-%E8%A8%93%E7%B7%B4%E6%95%99%E5%AD%B8-31e0062dc1d9)
