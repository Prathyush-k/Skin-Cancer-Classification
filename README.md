# Skin-Cancer-Classification

### The Dataset
https://www.kaggle.com/kmader/skin-cancer-mnist-ham10000

### Aim
The aim of this project is to classify the skin cancer images into the following 7 types:</br>
1) Melanocytic nevi</br>
2) Melanoma</br>
3) Benign keratosis</br>
4) Basal cell carcinoma</br>
5) Actinic keratose</br>
6) Vascular lesions</br>
7) Dermatofibroma
![Image description](category_sample.png)</br>
### Pre-Processing
* Read the HAM10000_metadata.csv with pandas and append the image paths to the dataframe</br>
* Append the cancer cell type names and indexes to the dataframe</br>
* Check which rows are duplicates of the same image and append a column with the details </br>
* Display the Statistical distributions of the data 
* Save the dataframe into .csv file
