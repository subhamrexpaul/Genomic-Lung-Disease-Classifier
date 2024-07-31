# Genomic Lung Disease Classifier: [Python, Keras, NumPy, Pandas, Scikit-learn, Matplotlib]

## Abstract

The main goal of our proposed framework is to identify and categorize different lung conditions like pneumonia using standard X-ray and CT scan images along with volume datasets. We have utilized three deep learning models - Sequential, Functional, and Transfer models - and trained them on publicly available datasets. Our models have achieved superior levels of accuracy, significantly benefiting humanity by enabling quicker disease detection. The sequential model, in particular, showcases an impressive F1 score of 98.55% and an accuracy of 98.43% for pneumonia.

## Introduction

Lung diseases can affect various parts of the respiratory system. Early detection of diseases like pneumonia can significantly improve survival rates. This project utilizes deep learning techniques to introduce a new approach for detecting lung diseases using X-ray and CT scan images.

## Code Explanation

This repository includes:

- **Data Preprocessing**: Scripts and notebooks for cleaning and preparing the X-ray and CT scan image data.
- **Model Training**: Implementation of Sequential, Functional, and Transfer learning models.
- **Model Evaluation**: Evaluation metrics to assess model performance.
- **Deployment**: Code for deploying the models as a web application or API.

## Functions

The main functions implemented in this project include:

- **Data Augmentation**: Techniques such as rotation, flipping, and scaling to augment the training data.
- **Model Architecture**: Custom neural network architectures for image classification tasks.
- **Training**: Functions to train the models using the prepared dataset.
- **Evaluation**: Functions to evaluate the models' accuracy, precision, recall, and F1-score.
- **Inference**: Functions to make predictions on new X-ray and CT scan images.

## Run the Code

To run the code for this project, follow these steps:

1. Clone the repository to your local machine:
    ```sh
    git clone https://github.com/subhamrexpaul/Genomic_Lung_Disease_Classifier.git
    ```
2. Navigate to the project directory:
    ```sh
    cd Genomic_Lung_Disease_Classifier
    ```
3. Set up a virtual environment and install the required dependencies:
    ```sh
    python -m venv venv
    source venv/bin/activate # On Windows use `venv\Scripts\activate`
    pip install -r requirements.txt
    ```
4. Run the data preprocessing script:
    ```sh
    python preprocess.py
    ```
5. Train the model:
    ```sh
    python train.py
    ```
6. Evaluate the model:
    ```sh
    python evaluate.py
    ```
7. (Optional) Deploy the model:
    ```sh
    python deploy.py
    ```

## Contributing

🛡️ This repository treasures personal assignments; contributions are reserved. Yet, share ideas through issues - your voice matters! 🌟

## Author

**Subham Paul**

## License

This project is licensed under the MIT License. You are free to modify and distribute the code for personal and educational purposes.
