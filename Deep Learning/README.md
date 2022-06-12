# Deep Learning Task

## Task Scenario

An orthopaedist is a medical doctor specializing in diagnosing and treating disorders related to the skeletal system. Part of their job is to distinguish between a healthy person and a person with Osteoarthritis by looking at their knee X-ray images.

Osteoarthritis: Osteoarthritis, commonly known as wear-and-tear arthritis, is a condition in which the natural cushioning between joints — cartilage — wears away. When this happens, the bones of the joints rub more closely against one another with less of the shock-absorbing benefits of cartilage. The rubbing results in pain, swelling, stiffness, decreased ability to move, and, sometimes, the formation of bone spurs.

![image](https://user-images.githubusercontent.com/86974424/173244996-dceede66-8006-474a-968e-689239af2036.png)

Healthy Knee Joint

![image](https://user-images.githubusercontent.com/86974424/173245032-8121f1b5-c3ec-455f-95ca-c9e48a274ee2.png)

Osteoarthritis Condition

You have to create a deep learning model that can detect if osteoarthritis is present or not in a given knee X-ray image.

Dataset: 

The Dataset contains three folders 

1. Test (845 images)
2. Train (2350 images)
3. Valid (641 images)

The train is a dataset that you will use to train your model.

The test is a dataset that you will use to test your model and find out the accuracy and confusion matrix.

Each of these folders has two folders 

1. Test:
 - Normal
 - Osteoarthritis
2. Train
 - Normal
 - Osteoarthritis
3. Valid
 - Normal
 - Osteoarthritis

Task:

Your task is to create a deep learning model that can provide the probability of having osteoarthritis for a given knee X-ray image.

Dataset:
https://drive.google.com/drive/folders/1y7AO4RHDLYYvjGMlZX2NBTpSFWho1Jyg?usp=sharing

##
## Solutions

![image](https://user-images.githubusercontent.com/86974424/173246941-820689b8-5934-4a56-a5d8-99561f81d76c.png)

### Training MobileNet Pretrained Model
![image](https://user-images.githubusercontent.com/86974424/173246986-cca1a1bf-231c-4190-ba59-a10910528394.png)

![image](https://user-images.githubusercontent.com/86974424/173247013-bd14c493-036c-4b22-880e-9f6b6c59e469.png)

### Accuracy Vs Val Accuracy
![image](https://user-images.githubusercontent.com/86974424/173247033-6d678bf7-19f9-417f-83fd-6b3dd68b80cd.png)

### Loss Vs Val Loss
![image](https://user-images.githubusercontent.com/86974424/173247059-671e287b-4181-4d9d-adb7-5f3a2bf13a41.png)

### Predicting Random Normal Images
![image](https://user-images.githubusercontent.com/86974424/173247097-47356cbb-5551-476b-b7b6-6438032a6232.png)

### Predicting Random Osteoarthritis Images
![image](https://user-images.githubusercontent.com/86974424/173247119-8775e372-9d32-46d4-927b-9473d1e04489.png)

## Note: These are the test data which I have used for prediction.
