# LeafGuard-AI
CNN-Based Plant Disease Classification Application

A computer vision model trained to detect and classify plant diseases from leaf images using Convolutional Neural Networks (CNNs). This notebook-based prototype demonstrates real-time classification, batch image preprocessing, performance evaluation, and color-coded disease mapping for actionable insights. 

**Note**: This is a simplified version, an early notebook iteration, for demonstration. Trained models are not included. The full deployed application includes a polished UI and extended features but is not public. A recorded demo of the full application in execution is available on request.

---

## Project Overview

This project is designed for use in precision agriculture to detect crop diseases early, enabling intervention before outbreaks spread. It supports both binary and multi-class classification of common plant diseases using deep learning.

**Key Features:**

- ~99.5% accuracy for binary classification (healthy vs. diseased)
- ~95% accuracy across 10 disease classes
- Simple GUI (Jupyter Widgets) supports model switching, data analysis, confusion matrices, and batch image classification
- Field-mapping logic (prototype version)

---

## Model Architecture, Training, and Data

- Convolutional Neural Network (CNN) with regularization
- Trained, validated, and tested on the **Tomato Leaf Disease Detection** dataset which contains 11,000 images
- Data Augmentation techniques include RandomRotation, RandomFlip, and RandomCutout.  

---

## Results

| Metric            | Value     |
|-------------------|-----------|
| Binary Accuracy   | ~99.5%    |
| Multi-Class Accuracy | ~95%   |

---

## Tech Stack & Dependencies

- Python
- Anaconda
- Jupyter Notebook
- TensorFlow / Keras
- Scikit-Learn
- NumPy
- Matplotlib
- Seaborn
- ipywidgets (for GUI prototype)

---

## Full Application Version

The full version includes:
- A full GUI (VS Code app)
- Batch uploading from image folders
- FastAPI deployment
- Scaled version capable of centrally processing images for multiple locations

A **recorded demo** showing the full application in execution is available upon request.

---

## Contact

For inquiries, demo requests, or collaboration:
[LinkedIn](https://www.linkedin.com/in/jeffrey-lynch-350930348/)

---

## License

This project is licensed under the MIT License — see the LICENSE file for details.
