# Deepfake-Detection-System
Unleash the truth! This project exposes deepfakes with deep learning. It combines pre-trained RestNext for image analysis with LSTM's memory for video sequences. By feeding RestNext's insights to LSTM, it learns to spot inconsistencies in manipulated videos.

## **Installation & Execution**
1. Download Trained Models:- [OneDrive](https://bit.ly/3wC9xX3)
2. save the models in ```main/models/``` directory.
3. Install dependencies from the requirements.txt
4. Run the web application.
5. Then adjust the frames you want to examine. As example I have taken 20 frames. ![Image title](Test%20Footage/image1.png)
6. Then fetch the video footage that you want to examine as shown below. ![Image title](Test%20Footage/image2.png)
7. Then Execute.

## **Output**
![Image title](Test%20Footage/image3.png)
![Image title](Test%20Footage/image4.png)
![Image title](Test%20Footage/image5.png)


## **Model Accuracy Chart**

| Model Name | No of videos | No of Frames | Accuracy |
|------------|--------------|--------------|----------|
|model_84_acc_10_frames_final_data.pt |6000 |10 |84.21461|
|model_87_acc_20_frames_final_data.pt | 6000 |20 |87.79160|
|model_89_acc_40_frames_final_data.pt | 6000| 40 |89.34681|
|model_90_acc_60_frames_final_data.pt | 6000| 60 |90.59097 |
|model_91_acc_80_frames_final_data.pt | 6000 | 80 | 91.49818 |
|model_93_acc_100_frames_final_data.pt| 6000 | 100 | 93.58794|
