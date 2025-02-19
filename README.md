 # 🏥 Skin Cancer Classification using DenseNet  

## 📌 Project Overview  
This repository contains a **DenseNet** deep learning model for **skin cancer classification**.  
The model is trained on the **HAM10000 dataset**, using **Stochastic Gradient Descent (SGD)** with **Focal Loss** to handle class imbalances.  

## 📂 Dataset: HAM10000  
We use the **HAM10000 dataset**, which contains **10,015 dermatoscopic images** categorized into **7 skin lesion classes**:  

| Class ID | Lesion Type                         | Abbreviation |
|----------|------------------------------------|--------------|
| 0        | Actinic Keratoses & Intraepithelial Carcinoma | **AKIEC** |
| 1        | Basal Cell Carcinoma              | **BCC**  |
| 2        | Benign Keratosis-like Lesions     | **BKL**  |
| 3        | Dermatofibroma                    | **DF**   |
| 4        | Melanocytic Nevi                  | **NV**   |
| 5        | Melanoma                          | **MEL**  |
| 6        | Vascular Lesions                  | **VASC** |

🔗 **Dataset Source**: [HAM10000 on Kaggle](https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000)  

## 🏗 Model Architecture  
The model is based on **DenseNet-29** and optimized using:  
✅ **SGD (Stochastic Gradient Descent)** – Effective for deep networks  
✅ **Focal Loss** – Handles class imbalances by focusing on hard-to-classify samples  
✅ **Data Augmentation** – Improves generalization by applying transformations  

  
   

## ⚙ Installation & Setup  
### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/your-username/skin-cancer-densenet.git
cd skin-cancer-densenet
