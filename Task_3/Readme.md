# Multimodal Machine Learning for Housing Price Prediction

## Project Overview

This project implements a multimodal machine learning model to predict housing prices by combining both structured (tabular) data and house images. The model extracts visual features from house images using a Convolutional Neural Network (CNN) and combines them with numerical and categorical features from the housing dataset to improve price prediction accuracy.

The project demonstrates how multiple data modalities can be integrated into a single deep learning model for regression tasks.

---

## Objectives

- Load and preprocess housing images and tabular data.
- Extract image features using a pre-trained Convolutional Neural Network (CNN).
- Preprocess numerical and categorical features from the housing dataset.
- Combine image features with tabular features using feature fusion.
- Train a multimodal regression model for house price prediction.
- Evaluate the model using regression metrics.
- Save the trained model for future predictions.

---

## Dataset

### Housing Sales Dataset

The dataset contains structured information about houses, including:

- Number of Bedrooms
- Number of Bathrooms
- Area (Square Feet)
- Location
- Year Built
- Other Property Features

### House Image Dataset

A collection of house images corresponding to each property in the tabular dataset.

---

## Technologies Used

- Python
- Pandas
- NumPy
- TensorFlow / Keras
- OpenCV
- Scikit-learn
- Matplotlib
- Joblib

---

## Model Architecture

### Image Feature Extraction

- Pre-trained CNN (e.g., ResNet50, MobileNetV2, or VGG16)
- Feature extraction from house images

### Tabular Data Processing

- Missing value handling
- Feature encoding
- Feature scaling

### Feature Fusion

- Concatenate image embeddings with tabular features
- Fully connected neural network for final regression

---

## Project Workflow

1. Load Housing Dataset
2. Load House Images
3. Image Preprocessing
4. Tabular Data Preprocessing
5. CNN Feature Extraction
6. Feature Fusion (Image + Tabular Data)
7. Train Regression Model
8. Evaluate Model Performance
9. Save the Trained Model

---

## Evaluation Metrics

The model performance is evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score (Coefficient of Determination)

---

## Project Structure

```
Housing-Price-Prediction/
│
├── housing_price_prediction.ipynb
├── housing_dataset.csv
├── images/
│   ├── house_001.jpg
│   ├── house_002.jpg
│   └── ...
├── trained_model.h5
├── requirements.txt
├── README.md
└── results/
```

---

## Skills Demonstrated

- Multimodal Machine Learning
- Image Processing
- Convolutional Neural Networks (CNNs)
- Feature Extraction
- Feature Fusion
- Regression Modeling
- Deep Learning
- Model Evaluation

---

## Results

The multimodal model successfully combines visual information from house images with structured housing data, leading to improved house price prediction performance compared to models trained using only tabular data.

---

## Future Improvements

- Use advanced Vision Transformer (ViT) models for image feature extraction.
- Perform hyperparameter tuning to optimize performance.
- Develop a Streamlit web application for real-time house price prediction.
- Deploy the trained model using Flask or FastAPI.
- Integrate geospatial information and satellite imagery for enhanced predictions.

---

## Author

**Nimra Ashraf**
