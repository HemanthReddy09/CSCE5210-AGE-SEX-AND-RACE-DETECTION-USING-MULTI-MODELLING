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

### FEATURES:
The dataset we want to use in this project is the UTKFace dataset. It is a large-scale dataset with over 20,000 images. The images are annotated with age, gender, and race. The images are in jpg format. The images are labeled as [age]_[gender]_[race]_[date&time].jpg. We will create a CSV file with image id and age, gender, and race adjacent to each image id from the dataset. We will be working on the images and the CSV file. The age feature is an integer value from o to 116 years; the gender is either 0 (male) or 1 (female); the race is an integer from 0 to 4 with each value indicating White, Black, Asian, Indian, and others (like Hispanic, Latino, Middle Eastern). 

### REFERENCES:
Vo, T., Nguyen, T., & Le, C. (2018). Race Recognition Using Deep Convolutional Neural Networks. Symmetry, 10(11), 564. https://doi.org/10.3390/sym10110564

Wu, X., Yuan, P., Wang, T., Gao, D., & Cai, Y. (2018). Race Classification from Face using Deep Convolutional Neural Networks. 2018 3rd International Conference on Advanced Robotics and Mechatronics (ICARM). https://doi.org/10.1109/icarm.2018.8610704

Darabant, A. S., Borza, D., & Danescu, R. (2021). Recognizing Human Races through Machine Learning—A Multi-Network, Multi-Features Study. Mathematics, 9(2), 195. https://doi.org/10.3390/math9020195

Rafique, I., Hamid, A., Naseer, S., Asad, M., Awais, M., & Yasir, T. (2019). Age and Gender Prediction using Deep Convolutional Neural Networks. 2019 International Conference on Innovative Computing (ICIC). https://doi.org/10.1109/icic48496.2019.8966704

Saxena, A., Singh, P., & Narayan Singh, S. (2021). Gender and Age detection using Deep Learning. 2021 11th International Conference on Cloud Computing, Data Science & Engineering (Confluence). https://doi.org/10.1109/confluence51648.2021.9377041
