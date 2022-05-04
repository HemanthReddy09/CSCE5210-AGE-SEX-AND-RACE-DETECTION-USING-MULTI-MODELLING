# CSCE5210-AGE-SEX-AND-RACE-DETECTION-USING-MULTI-MODELLING

## AGE, SEX, AND RACE DETECTION USING MULTI MODELLING

![image](https://user-images.githubusercontent.com/90491571/166619191-286fc00b-b74a-458c-91ed-427fa8f62f24.png)

### TEAM:
#### MANISH REDDY RADHA REDDY
#### HEMANTH REDDY YERRAMREDDY
#### CHANDRAKANTH MANDALPU

### MOTIVATION:
While we were previously working on projects based on CNN, we were trying to predict just a single characteristic or output variable. Like the age of a person or animal, gender of a person, etc. We then started to think about how to predict various output variables all at once when given an input. While researching this topic, we came across multi-model machine learning or deep learning techniques. Hence, this inquisitiveness motivated us to take up this project idea. We want to implement a multi-modal deep learning technique to detect a person’s age, sex, and race/ethnicity when given an image input.

### OBJECTIVE:
The project is based on detecting a human's face and determining the various characteristics. These features would include Age, Sex, and Race/Ethnicity. These would be the model’s features to classify the image and predict the subject's age, gender, and race. This project would be helpful to understand image processing and computer vision techniques. We intend to develop our own CNN model to make out predictions. Also, we want to use a state-of-the-art model in this project. The project would also use transfer learning to develop a multi-model to determine the age, sex from one model, and race from another model. This should enable the model to have significantly higher accuracy than previous ones. We would implement all these techniques, compare the results, and provide a detailed report. 

### The dataset
Link: https://drive.google.com/drive/folders/1mRyGIAfbLDdq8auCT5MvmdJMcSx_555h 

The UTKFace dataset is a large dataset composed of over 20 thousand face images with their respectivce annotations of age, gender and ethnicity. The images are properly cropped into the face region, but display some variations in pose, illumination, resolution, etc.

In order to retrieve the annotations of each record, we need to parse the filenames. Each record is stored in the following format: [age]_[gender]_[race]_[date&time].jpg
Where: - age is an integer from 0 to 116 - gender is an integer in which 0 represents male and 1 represents female - race is an integer from 0 to 4, denoting white, black, asian, indian and others, respectively - date and time, denoting when the picture was taken. 

### How did we work on extracting the dataset from the Data file?
The data file that we used was UTKFace dataset and that file consists of images with their age, race, sex of the person in the image as the image file name. As the age, race, sex of the image in the image name was divide with “_”, we used python “.split(“_”) and separated the values from the image file name and then stored each values in separate lists and then finally created a dataset using the image path , age , sex, race as the columns in the dataset.

### How to execute the model?
As while we executed the model we saved the trained weights of the model, so using that we can run the trained model for the predictions whenever we needed them. As we worked on three models such as proposed model, existing model, transfer learning model we saved the weights of each and every trained model and their historys to see the visualizations of the accuracy and losses of the model. When we come to the prediction of a custom data, then we need create a dataset and then we need to pass the indices of the dataset to the last code snipped that we have in the ipynb notebook that we have submitted and the results will be displayed as shown in the below figure-1.


