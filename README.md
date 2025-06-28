# 🔥 Machine Learning & Remote Sensing for Wildfire and Spatial Risk Management

Welcome to the  repository of Workshop Machine Learning & Remote Sensing for Wildfire and Spatial Risk Management prepared for participants of Split Remote Sensing Summer School 2025 [https://splitremotesensing.com/] ! This collection of Jupyter notebooks and spatial data supports the training on using **machine learning and remote sensing** for **wildfire detection, monitoring**, and **spatial risk assessment**.

The content is structured to guide participants through downloading remote sensing data, applying ML models, and using patch-based processing approaches for large spatial datasets.



---

## 📚 Workshop Structure

### 1. 📥 **Data Download**
- Learn how to access and organize satellite imagery (e.g. MODIS, Sentinel).
- Automated scripts and notebooks to download and format data for modeling.

### 2. 🤖 **Machine Learning - Classification Models**
- Supervised learning: Random Forest, SVM, and Logistic Regression
- Burned area classification  
- Model evaluation  
- Use  model to classify new images 

### 2. 🤖 **Machine Learning - Regression  Models**
- Supervised learning: Linear, Polynomial and Ridge regression
- Burned area   and fire risk prediction
- Model evaluation  
- Use  model to create new images 

### 4. 🧩 **Patch-Based Analysis**
- Divide satellite images into small "patches" for training
- Use Convolution based model and attention mechanism
 
---
 
 
 
 
## 🛠 Requirements

Install Python dependencies:

```bash
pip install -r requirements.txt
 ```
---

OR 

---

☁️ Run in Google Colab
 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ljiljana44/WildFire_Workshop/blob/main/00_Copy_to_google_colab.ipynb)


✅ Step-by-step:

Open  https://colab.research.google.com 

Open New notebook

Run the cell to mount Google Drive 

 ```
from google.colab import drive
drive.mount('/content/drive')
```

Run the following code cell to clone the repository:
 ```
%%bash
# Clone the repo
cd /content/drive/MyDrive/
mkdir -p WildFire_RemoteSensing_workshop
cd WildFire_RemoteSensing_workshop
git clone https://github.com/ljiljana44/WildFire_RemoteSensing


```
 



📫 Contact
For questions or collaboration ideas, feel free to reach out:

GitHub: @ljiljana44

Email: ljiljana@fesb.hr
