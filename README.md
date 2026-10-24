# Kidney Disease Prediction Using Machine Learning

This project uses machine learning and deep learning to analyse kidney-related data through two independent prediction systems.

## Project Modules
- **CKD Prediction:** Compares eight machine-learning models using clinical tabular data to classify CKD and Not CKD.
- **CT Image Classification:** Uses MobileNetV2 transfer learning to classify kidney CT images into Cyst, Normal, Stone, and Tumor.
- **Explainable AI:** Uses SHAP to interpret tabular predictions and Grad-CAM to visualize image regions influencing predictions.

## Technologies Used
Python, Pandas, NumPy, Scikit-learn, TensorFlow/Keras, SHAP, and Matplotlib.

## Datasets
- [CKD Clinical Dataset](https://www.kaggle.com/datasets/mansoordaku/ckdisease)
- [Kidney CT Image Dataset](https://www.kaggle.com/datasets/nazmul0087/ct-kidney-dataset-normal-cyst-tumor-and-stone)

## Results
- Tabular models achieved up to **100% reported test accuracy** on an 80-record test set.
- The CT image classifier achieved **94% reported test accuracy** on 1,867 test images.

These results require further validation and do not establish clinical reliability.

## Disclaimer
This project is intended for educational and research purposes only. It is not a clinically validated diagnostic system.

## Authors
- Parth Parkhi
- Rahul Malani

**Mentor:** Dr. Prerna Mishra  
**Institute:** Symbiosis Institute of Technology, Nagpur
