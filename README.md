# Ai-based-Disease-Detection-System
HealthCure is a website in which 4 disease detections models are there using the power of AI. Brain Tumour detection: Used CNN accuracy is 92.42% Breast Cancer Detection: Used Random Forest accuracy was 99.53% Diabetes detection: Used SVM accuracy was 78.66%. Pneumonia Detection: Used custom CNN accuracy was 98.16%
## Steps to run this website:
1. Download anaconda https://www.anaconda.com/download/
2. Create a conda environment and install the required libraries
   
   conda create -n ayurcare python=3.9
   conda activate ayurcare 
   pip install opencv-python numpy tensorflow scikit-learn==0.24.2 imutils flask xgboost
   
4. When you have successfully created the environment, installed the required libraries, and activated it, simply run the following command in the terminal.

   flask run

### The Datasets used to train the model are:
- [Brain Tumour dataset:](https://www.kaggle.com/navoneel/brain-mri-images-for-brain-tumor-detection)
- [Breast Cancer dataset:](https://web.inf.ufpr.br/vri/databases/breast-cancer-histopathological-database-breakhis/)
- [Diabetes dataset:](https://www.kaggle.com/datasets/saurabh00007/diabetescsv)
- [Pneumonia Dataset1:](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)
- [Pneumonia Dataset2:](https://www.kaggle.com/paulti/chest-xray-images).

####   Preview of our website
   ![Screenshot 2023-11-21 180504](https://github.com/CodewithAbhi7/Ai-based-Disease-Detection-System/assets/112254825/2502af14-0eec-4828-8b2a-bccf98b43aa0)
   ![Screenshot 2023-11-07 230919](https://github.com/CodewithAbhi7/Ai-based-Disease-Detection-System/assets/112254825/17285474-ec6f-4041-9881-0d23841fa8d2)
   ![Screenshot 2023-11-07 231035](https://github.com/CodewithAbhi7/Ai-based-Disease-Detection-System/assets/112254825/904a4039-3bbd-43b8-8484-85d9a11ee61e)
