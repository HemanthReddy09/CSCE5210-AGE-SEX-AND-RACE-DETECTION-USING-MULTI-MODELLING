# CSCE5210-AGE-SEX-AND-RACE-DETECTION-USING-MULTI-MODELLING

## AGE, SEX, AND RACE DETECTION USING MULTI MODELLING

### TEAM:
#### MANISH REDDY RADHA REDDY
#### HEMANTH REDDY YERRAMREDDY
#### CHANDRAKANTH MANDALPU

### MOTIVATION:
While we were previously working on projects based on CNN, we were trying to predict just a single characteristic or output variable. Like the age of a person or animal, gender of a person, etc. We then started to think about how to predict various output variables all at once when given an input. While researching this topic, we came across multi-model machine learning or deep learning techniques. Hence, this inquisitiveness motivated us to take up this project idea. We want to implement a multi-modal deep learning technique to detect a person’s age, sex, and race/ethnicity when given an image input.

### SIGNIFICANCE:
The primary significance of the project is to extract more than one feature from an image and predict those features as target variables. Also, we want to introduce the idea of multi-model deep learning to the class as it is still a newly emerging topic. Other significant features of our include: The face image would have much soft biometrics. These are age, sex, and race. These features would prove helpful to identify a person from any surveillance. This would enable authorities to determine a fugitive or person of interest accurately. There haven’t been any significant race classification benchmarks for established comparison. 

### OBJECTIVE:
The project is based on detecting a human's face and determining the various characteristics. These features would include Age, Sex, and Race/Ethnicity. These would be the model’s features to classify the image and predict the subject's age, gender, and race. This project would be helpful to understand image processing and computer vision techniques. We intend to develop our own CNN model to make out predictions. Also, we want to use a state-of-the-art model in this project. The project would also use transfer learning to develop a multi-model to determine the age, sex from one model, and race from another model. This should enable the model to have significantly higher accuracy than previous ones. We would implement all these techniques, compare the results, and provide a detailed report. 

### The dataset
The UTKFace dataset is a large dataset composed of over 20 thousand face images with their respectivce annotations of age, gender and ethnicity. The images are properly cropped into the face region, but display some variations in pose, illumination, resolution, etc.

In order to retrieve the annotations of each record, we need to parse the filenames. Each record is stored in the following format: [age]_[gender]_[race]_[date&time].jpg
Where: - age is an integer from 0 to 116 - gender is an integer in which 0 represents male and 1 represents female - race is an integer from 0 to 4, denoting white, black, asian, indian and others, respectively - date and time, denoting when the picture was taken


