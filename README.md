# 🔥 Machine Learning & Remote Sensing for Wildfire and Spatial Risk Management

Welcome to the workshop repository! This collection of Jupyter notebooks and spatial data supports the training on using **machine learning and remote sensing** for **wildfire detection, monitoring**, and **spatial risk assessment**.

The content is structured to guide participants through downloading remote sensing data, applying ML models, and using patch-based processing approaches for large spatial datasets.

---

## 📚 Workshop Structure

### 1. 📥 **Data Download**
- Learn how to access and organize satellite imagery (e.g. MODIS, Sentinel).
- Automated scripts and notebooks to download and format data for modeling.

### 2. 🤖 **Machine Learning Models**
- Supervised learning: Random Forest, SVM, and Logistic Regression
- Burned area classification and fire risk prediction
- Model evaluation  
- Use  model to classify new images 

### 3. 🧩 **Patch-Based Analysis**
- Divide satellite images into small "patches" for training
- Use Convolution based model and attention mechanism
 
---
 
---
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ljiljana44/WildFire_Workshop/blob/main/01_download_and_explore.ipynb)
 
## 🛠 Requirements

Install Python dependencies:

```bash
pip install -r requirements.txt


☁️ Run in Google Colab
You can run this workshop directly in Google Colab without installing anything locally.

✅ Step-by-step:
Open a new notebook at https://colab.research.google.com

Run the following code cell to clone the repository:
 
# Clone the repo
from google.colab import drive
drive.mount('/content/drive')
 

%%bash
cd /content/drive/MyDrive/
mkdir -p WildFire_RemoteSensing_workshop
cd WildFire_RemoteSensing_workshop
git clone https://github.com/ljiljana44/WildFire_RemoteSensing


[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ljiljana44/WildFire_Workshop/blob/main/01_download_and_explore.ipynb)


📫 Contact
For questions or collaboration ideas, feel free to reach out:

GitHub: @ljiljana44

Email: ljiljana@fesb.hr
