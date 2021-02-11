## Automatic Number Plate Recognition (ANPR)

ANPR is process of recognizing the characters of number plate of a vehicle. The project has two modules Number plate detection, Character recognition. Number plate Detection is done through YOLO V3 model. The model is trained on Kaggle data set available on Kaggle website. Character recognition is done using Pytesseract.

## Flow Chart

![image](https://user-images.githubusercontent.com/69388951/107684339-7c50ec00-6cc4-11eb-9614-a19d80c25a44.png)

## YOLO V3


The pipeline of model is shown below. The model is trained on Kaggle dataset. Use this link to download dataset https://www.kaggle.com/andrewmvd/car-plate-detection. The data is annotated through Label image tool. It is a graphical image annotation tool. It is used to label objects in images. The tool returns files in XML which has images coordinates, height and width.  The model is trained on images and their corresponding XML files. 

![image](https://user-images.githubusercontent.com/69388951/107684645-d5b91b00-6cc4-11eb-994e-37141aef83f6.png)




The working of YOLO V3 is shown in below figure. 

![image](https://user-images.githubusercontent.com/69388951/107684676-e073b000-6cc4-11eb-8c80-9bb1a3fa4974.png)


## Pytesseract

Pytesseract is an optical character recognition (OCR) tool for python. It recognize and “read” the text embedded in images. It is used to detect text from number plate.

## Output


![image](https://user-images.githubusercontent.com/69388951/107685126-7576a900-6cc5-11eb-8f7c-5018ba58d170.png)



![image](https://user-images.githubusercontent.com/69388951/107685152-7b6c8a00-6cc5-11eb-9b8d-5e352687ae6d.png)
