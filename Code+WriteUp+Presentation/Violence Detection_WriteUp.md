# Violence Detection in Smart Cities Using Deep Learning
## Introduction
Citizen safety in modern urban environments is an important aspect of life quality. Computer Vision in smart city applications often involves the automatic detection Of dangerous situations with the goal to ensure the safety of residents with smart video surveillance. Such dangerous situations can be fighting, brawls, robberies, and more.

The aim of this project is to develop automatic system to detect dangerous situations

## Data Description
Our Dataset is from kaggle and it contains 1000 Violence and 1000 non-violence videos collected from youtube videos, violence videos in our dataset contain many real street fights situations in several environments and conditions. non-violence videos are collected from many different human actions like sports, eating, walking …etc.


## Algorithms
1.  Data Preprocessing
     Convert each video to 40 frame
 2. Deep Learning 
   - Modeling
    <br/> <br/> 
     |                   | Traning            | Validation         |
     |-------------------|--------------------|--------------------|
     |   ConvLSTM2D V1   |     0.99           |     0.83           |
     |   ConvLSTM2D V2   |     0.94           |     0.73           |
     |   ConvLSTM2D V3   |     0.64           |     0.70           |
     |   Conv1D V4       |     0.87           |     0.70           |
     |   ConvLSTM2D V5   |     0.98           |     0.86           |
     |   ConvLSTM2D V6   |     1.00           |     0.86           |
     
   - Transfer Learning
     <br/> <br/> 
     |           | Traning            | Validation         |         Test      |
     |-----------|--------------------|--------------------|--------------------
     |   VGG16   |     0.94           |     0.88           |      0.88         |
  
    
     
 ## Tools
- google colab  
- Python Libraries:
    - NumPy
    - Keras
    - TensorFlow
    - Sklearn
    - Matplot
      

## Conclusion
The project successfully achieve it's goal using **Deep Learning**  with **0.88%** accuracy .

 
