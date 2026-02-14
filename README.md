# Nail Disease Detection Project

This project implements a Convolutional Neural Network (CNN) to classify various nail diseases from images. It uses a Deep Learning approach to identify 17 different types of nail conditions.

## 📌 Project Overview
The goal of this project is to assist in the early diagnosis of nail diseases using computer vision. The model is trained on a dataset of nail images categorized into different disease classes.

## 📂 Dataset
The dataset consists of images belonging to **17 classes** of nail diseases:
1.  Darier's disease
2.  Muehrcke's lines
3.  Alopecia areata
4.  Beau's lines
5.  Bluish nail
6.  Clubbing
7.  Eczema
8.  Half and half nails (Lindsay's nails)
9.  Koilonychia
10. Leukonychia
11. Onycholysis
12. Pale nail
13. Red lunula
14. Splinter hemorrhage
15. Terry's nail
16. White nail
17. Yellow nails

-   **Image Size**: 128x128 pixels
-   **Data Augmentation**: Rescaling, Rotation, Zoom, Horizontal Flip

## 🧠 Model Architecture
The model is built using **TensorFlow/Keras** and consists of:
-   **Convolutional Layers**: For feature extraction.
-   **Max Pooling Layers**: For downsampling.
-   **Flatten Layer**: To convert 2D feature maps to 1D vectors.
-   **Dense Layers**: Fully connected layers for classification.
-   **Dropout**: To prevent overfitting.
-   **Output Layer**: Softmax activation for multi-class classification (17 classes).

## 🚀 How to Run
1.  **Clone the repository**:
    ```bash
    git clone https://github.com/parthshinge/Nail_Disease_Project.git
    cd Nail_Disease_Project
    ```
2.  **Install dependencies**:
    ```bash
    pip install tensorflow pandas numpy matplotlib seaborn
    ```
3.  **Run the Notebook**:
    Open `Nail_Disease_Project.ipynb` in Jupyter Notebook or Google Colab to see the training process and results.

## 📊 Results
The model is trained for 15 epochs using the Adam optimizer and Categorical Crossentropy loss.

## 👤 Author
**Parth Shinge**