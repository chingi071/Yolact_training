# YOLACT_training
Use YOLACT training instance segmentation, the training set data is downloaded from [roboflow Raccoon Dataset](https://public.roboflow.com/object-detection/raccoon) and then labeled.

The labeled data is placed in the [raccoon_dataset folder](https://drive.google.com/file/d/1ivRtpdIOs3VG0j_IEtroUJG8qsoeBk-Z/view?usp=sharing).

## Create dataset
Before training, first convert the training data into COCO format. 

Execute create_dataset.ipynb to convert the training data format.

## Training
Execute training.ipynb for training. 

## Raccoon instance segmentation model
The trained model is placed in [weights](https://drive.google.com/file/d/1HoTXAyto4RlgafjjdMrLb3nMnmkdwd2v/view?usp=sharing)

## Predict result
The predicted results are as follows
![image](https://github.com/chingi071/Yolact_training/blob/main/output_image.png)

## Prevent Colab from automatically disconnecting
Press F12 on the Colab page, paste the following Code in the Console and press Enter

    function ConnectButton(){
    console.log("Connect pushed"); 
    document.querySelector("#connect").click() 
    }
    setInterval(ConnectButton,60000);

## Flow
The detailed process can refer to my Medium: [YOLACT 訓練教學](https://medium.com/ching-i/yolact-%E8%A8%93%E7%B7%B4%E6%95%99%E5%AD%B8-31e0062dc1d9)
