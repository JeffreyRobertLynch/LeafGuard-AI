# LeafGuard-AI
CNN-Based Plant Disease Classification Application

A computer vision model trained to detect and classify plant diseases from leaf images using Convolutional Neural Networks (CNNs). This notebook-based project demonstrates real-time classification, batch image preprocessing, performance evaluation, and color-coded disease mapping for actionable insights. 

**Note**: This is a simplified version for demonstration. Trained models are not included. The full deployed application includes a polished UI and extended features but is not public. A recorded demo of the full application in execution is available on request.

---

## 📌 Project Overview

This project is designed to help detect crop diseases early, enabling intervention before outbreaks spread. It supports both binary and multi-class classification of common plant diseases using deep learning.

**Key Features:**
- ~99.5% accuracy for binary classification (healthy vs. diseased)
- ~95% accuracy across 38 disease classes
- Batch image classification and simple GUI (Jupyter Widgets)
- Field-mapping logic (prototype version)

---

## 🧠 Model Architecture

- Convolutional Neural Network (CNN) with regularization
- Trained on the **PlantVillage dataset** with ~54K labeled images
- Augmentation pipeline for real-world variability
- Early stopping and checkpointing to prevent overfitting

---

## 📊 Results

| Metric            | Value     |
|-------------------|-----------|
| Binary Accuracy   | ~99.5%    |
| Multi-Class Accuracy | ~95%   |
| F1 Score          | High across all classes |
| False Positives   | Minimal (due to augmentation & regularization) |

---

## Tech Stack

- Python
- TensorFlow / Keras
- Jupyter Notebook
- Scikit-Learn
- NumPy 
- ipywidgets (for GUI prototype)

---

## How to Run

1. Clone the repository  
   `git clone https://github.com/yourusername/leafscan-ai.git`

2. Navigate to the folder  
   `cd leafscan-ai`

3. Install requirements (see `requirements.txt`)  
   `pip install -r requirements.txt`

4. Launch the notebook  
   `jupyter notebook`

5. Open `LeafScan.ipynb` and run all cells.

---

## Full Application Version

The full version includes:
- A full GUI (VS Code app)
- Batch uploading from image folders
- FastAPI deployment
- Scaled version capable of centrally processing images for multiple locations
- Model Switching

A **recorded demo** showing the full application in execution is available upon request.

---

## 📬 Contact

For inquiries, demo requests, or collaboration:
🔗 [LinkedIn](https://www.linkedin.com/in/yourprofile/)

---

## ⚖️ License

This project is licensed under the MIT License — see the LICENSE file for details.
