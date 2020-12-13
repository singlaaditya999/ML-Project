# Gender Prediction
In the gender.ipynb we train the Convolution Neural Network using the age, gender, ethnicity data available on
https://www.kaggle.com/nipunarora8/age-gender-and-ethnicity-face-data-csv

The model so trained is stored gender_detector.model file.

detect_gender_image.py does gender prediction provided the directory of the input.
## Usage : python detect_gender_image.py -i [directory]


detect_gender_video.py uses the real time input from the webcam to do gender detection.
##Usage : python detect_gender_video.py


detect_gender_video_2.py does gender prediction on an input video.
## Usage : python detect_gender_video_2.py
