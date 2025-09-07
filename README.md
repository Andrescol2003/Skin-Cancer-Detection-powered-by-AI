# Skin Cancer Detection – Deep Learning (CNNs)

## Overview
This project applies **Deep Learning** to classify skin lesions as benign or malignant using dermatoscopic images from the HAM10000 dataset.  
The objective is to explore how Convolutional Neural Networks (CNNs) can assist in early skin cancer detection and support medical decision-making.  

---

## Project Structure
- `notebooks/` → Jupyter notebooks with preprocessing, model training, and evaluation.  
- `data/` → (Not included in repo – dataset can be found on [Kaggle: HAM10000](https://www.kaggle.com/kmader/skin-cancer-mnist-ham10000)).  
- `models/` → Saved CNN model weights
- `requirements.txt` → Python dependencies.  

---

##  Methods & Tools
- Data Processing: Image augmentation, resizing, train/test split  
- Modeling: Convolutional Neural Networks (CNNs), Transfer Learning (MobileNetV2)  
- Evaluation Metrics: Accuracy, AUC (Area Under Curve), Confusion Matrix  
- Libraries: TensorFlow, Keras, NumPy, Matplotlib  

---

##  Results
- Implemented transfer learning** with MobileNetV2.  
- Achieved AUC: 0.90 in distinguishing benign vs malignant lesions.  
- Improved model robustness with data augmentation and early stopping.
