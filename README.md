# Ai-based-Disease-Detection-System
AyurCare is a website in which 4 disease detections models are there using the power of AI. Brain Tumour detection: Used CNN accuracy is 92.42% Breast Cancer Detection: Used Random Forest accuracy was 99.53% Diabetes detection: Used SVM accuracy was 78.66%. Pneumonia Detection: Used custom CNN accuracy was 98.16%
## Steps to run this website:
1. Download anaconda https://www.anaconda.com/download/
2. Create a conda environment and install the required libraries
   ```
   conda create -n ayurcare python=3.9
   conda activate ayurcare 
   pip install opencv-python numpy tensorflow scikit-learn==0.24.2 imutils flask xgboost
   ```
4. When you have successfully created the environment, installed the required libraries, and activated it, simply run the following command in the terminal.
   ```
   flask run
   ```
### The Datasets used to train the model are:
- [Brain Tumour dataset:](https://www.kaggle.com/navoneel/brain-mri-images-for-brain-tumor-detection)
- [Breast Cancer dataset:](https://web.inf.ufpr.br/vri/databases/breast-cancer-histopathological-database-breakhis/)
- [Diabetes dataset:](https://www.kaggle.com/datasets/saurabh00007/diabetescsv)
- [Pneumonia Dataset1:](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)
- [Pneumonia Dataset2:](https://www.kaggle.com/paulti/chest-xray-images).

####   Preview of our website
![Screenshot 2023-11-22 171445](https://github.com/CodewithAbhi7/Ai-based-Disease-Detection-System/assets/112254825/2e0c4f7e-f194-4592-a815-57b9aa07c691)
![Screenshot 2023-11-07 230919](https://github.com/CodewithAbhi7/Ai-based-Disease-Detection-System/assets/112254825/f431f846-bf58-48b1-9192-af7ac6a62059)
![Screenshot 2023-11-07 231035](https://github.com/CodewithAbhi7/Ai-based-Disease-Detection-System/assets/112254825/80da85e7-4861-4d79-adf9-23e5312030fb)

