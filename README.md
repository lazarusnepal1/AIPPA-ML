# AIPPA-ML 

## Machine Learning Program that runs Transfer Learning Inception V3 using Keras
- By Lazarus Nepal

### Overview of the Algorithm and Modules
For this project, we have developed a plant disease recognition model, based on leaf image classification. This program uses Transferred Learning Inception V3 algorithms using Keras. The program uses various other modules like numpy, glob, matplotlib and so on.

### Overview of the used Dataset
For the project, Lazarus Nepal group has used the dataset provided by PlantVillage. This public dataset consists of 54,305 images of diseases and healthy plant leaves collected under controlled conditions. The dataset includes 38 sub-directories with their respective dataset, it covers 14 different species of crops i.e. Apple, Cherry, Pepper, Soy, Strawberry, Blueberry, Grape, Orange, Peach, Potato, Raspberry, Squash and Tomato. It contains images of 17 basic diseases, 4 bacterial diseases, 2 diseases caused by mold (oomycete), 2 viral diseases and 1 disease caused by a mite. 12 crop species also have healthy leaf images that are not visibly affected by disease.


## Functional Requirements of the Code
- It should run on Google Colab.
- The Google drive account that contains the Dataset should be mounted to the Google colab. The code for that is given in the first cell of the .ipynb file itself. This helps the code to perform read and write operations on the google drive.

For the program to run, a Google Drive account should be mounted that contains a dataset. Then it accesses the data, trains the program, visualizes the training results and finally outputs a trained data in .H5 format. The .H5 file is then converted into .tflite to be able to run the android app built by Lazarus Nepal. The program uses the mounted Google Drive to perform the other various Read and Write operations as well.

## Note
This project was built for the KU Hackfest 2021. Due to the time limitation there are still a lot of changes that could be made in the code itself including the optimization process. The model can be improved by changing the training logic, by adding efficient optimization code and by changing some hyperparameters.

## Conclusion
The program provides a very accurate training algorithm with the light weight output as .tflite file. The output file can be easily integrated in an offline mobile application. The program shows the output of the trained model in visualized chart format. It also provides a lot of flexibility for customization. Since this program is built to run on Google Colab, the training and visualization process does not put burden on the local computer resources.  Kaggle can also be used as an alternative platform for training the datasets.

## Check the Android part of this project
[AIPPA - The Plant Doctor (Android Part)](https://github.com/lazarusnepal1/AIPPA-ML-Android)
