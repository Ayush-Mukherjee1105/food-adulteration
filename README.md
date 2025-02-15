# Food Adulteration Detection

This project focuses on detecting food adulteration using various machine learning models. It involves data cleaning, exploratory data analysis (EDA), and model evaluation to identify adulterants in different food products.

## Table of Contents
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Machine Learning Models](#machine-learning-models)
- [Results](#results)
- [Future Enhancements](#future-enhancements)
- [Contributors](#contributors)

## Dataset
The dataset includes:
- **Product Name**: Name of the food item
- **Brand**: Manufacturer/Brand details
- **Adulterant**: The type of adulterant detected
- **Severity**: The severity level of adulteration
- **Category**: Type of food item
- **Detection Method**: The method used to detect adulteration

## Technologies Used
- **Programming Language**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Development Platform**: Google Colab

## Project Structure
```
food-adulteration/
│-- data/                 # Dataset files
│-- notebooks/            # Jupyter notebooks for EDA and modeling
│-- models/               # Saved machine learning models
│-- scripts/              # Python scripts for data preprocessing and training
│-- README.md             # Project documentation
```

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/IshanDey007/food-adulteration.git
   cd food-adulteration
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
Run the Jupyter notebook in Google Colab or locally:
```bash
jupyter notebook
```
Follow the steps in the notebooks to preprocess data, train models, and evaluate results.

## Machine Learning Models
The project uses multiple classification models:
- Support Vector Machine (SVM)
- k-Nearest Neighbors (KNN)
- Logistic Regression
- Random Forest Classifier
- Decision Tree
- Naive Bayes

## Results
The models are evaluated using accuracy, precision, recall, and F1-score. Results are visualized using confusion matrices and ROC curves.

## Future Enhancements
- Improve model accuracy with hyperparameter tuning
- Implement deep learning models for better classification
- Develop a web or mobile application for real-time detection

## Contributors
- **Ayush Mukherjee** - Project Owner and Frontend Developer
- **Ishan Dey** - Project Owner and Backend Developer

Feel free to contribute by raising issues or submitting pull requests!


