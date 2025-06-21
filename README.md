# 🗣️ Lip Reader

**Lip Reader** is an AI-powered application that takes video input and predicts spoken words by analyzing lip movements. It uses deep learning models and provides an interactive interface via Streamlit.

## 📁 Folder Structure

app/
├── pycache/
├── animation.gif
├── modelutil.py
├── Streamlitapp.py
├── utils.py
├── LipNet.ipynb
├── models - checkpoint 50.zip
└── models - checkpoint 96.zip


## 🚀 How to Run

1. Install dependencies:

```bash
pip install streamlit numpy opencv-python torch torchvision
```
Unzip the model files:

models - checkpoint 50.zip

models - checkpoint 96.zip

Run the Streamlit app:

streamlit run Streamlitapp.py
📦 Model Checkpoints
Pre-trained model checkpoints are provided to make predictions without retraining. Make sure they are unzipped and accessible.

📓 Jupyter Notebook
Use LipNet.ipynb to experiment with training or testing the model.
