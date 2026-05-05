# AI-Based Disease Detection System (AyurCare)

AyurCare is a multi-model AI-powered healthcare web application designed to detect critical diseases using machine learning and deep learning techniques. The platform integrates multiple predictive models into a single interface, enabling fast and accessible preliminary diagnosis.

---

##  Key Features

- Multi-Disease Detection System in one unified platform  
- Web-based Interface built using Flask  
- Real-time Predictions from trained ML/DL models  
- High Accuracy Models across different medical domains  

---

## Models Implemented

| Disease | Model Used | Accuracy |
|--------|-----------|----------|
| Brain Tumor Detection | Convolutional Neural Network (CNN) | 92.42% |
| Breast Cancer Detection | Random Forest Classifier | 99.53% |
| Diabetes Detection | Support Vector Machine (SVM) | 78.66% |
| Pneumonia Detection | Custom CNN | 98.16% |

---

## Tech Stack

- **Frontend:** HTML, CSS  
- **Backend:** Flask  
- **Machine Learning:** Scikit-learn, TensorFlow, XGBoost  
- **Computer Vision:** OpenCV, Imutils  
- **Environment:** Anaconda (Python 3.9)

---

## How to Run Locally

```bash
# Create environment
conda create -n ayurcare python=3.9

# Activate environment
conda activate ayurcare

# Install dependencies
pip install opencv-python numpy tensorflow scikit-learn==0.24.2 imutils flask xgboost

# Run the application
flask run
```

## The Datasets used to train the model are:
- [Brain Tumour dataset](https://www.kaggle.com/navoneel/brain-mri-images-for-brain-tumor-detection)
- [Breast Cancer dataset](https://web.inf.ufpr.br/vri/databases/breast-cancer-histopathological-database-breakhis/)
- [Diabetes dataset](https://www.kaggle.com/datasets/saurabh00007/diabetescsv)
- [Pneumonia Dataset1](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)
- [Pneumonia Dataset2](https://www.kaggle.com/paulti/chest-xray-images).

##   Preview of the website
![Screenshot 2023-11-22 171445](https://github.com/CodewithAbhi7/Ai-based-Disease-Detection-System/assets/112254825/2e0c4f7e-f194-4592-a815-57b9aa07c691)
![Screenshot 2023-11-07 230919](https://github.com/CodewithAbhi7/Ai-based-Disease-Detection-System/assets/112254825/f431f846-bf58-48b1-9192-af7ac6a62059)
![Screenshot 2023-11-07 231035](https://github.com/CodewithAbhi7/Ai-based-Disease-Detection-System/assets/112254825/80da85e7-4861-4d79-adf9-23e5312030fb)
