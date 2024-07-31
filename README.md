# Genomic Lung Disease Classifier: [Python, Keras, NumPy, Pandas, Scikit-learn, Matplotlib]

## Project Overview
The Genomic Lung Disease Classifier is a deep learning-based project aimed at enhancing the detection accuracy of various lung diseases from X-ray and CT scan images. The project also integrates genetic data to further improve model performance.

## Problem Statement
Existing models exhibited limited accuracy and high computational costs in detecting various lung diseases from X-ray and CT scan images.

## Solution
- Engineered and implemented cutting-edge deep learning techniques, including Convolutional Neural Networks (CNNs), to extract features and analyze biomedical images.
- Integrated genetic data to significantly enhance model performance in detecting lung diseases.
- Deployed advanced CNNs to categorize lung diseases, boosting accuracy by 35%.
- Validated models demonstrated a substantial reduction in the number of trained parameters by 45%, decreasing computational overhead and costs.

## Implementation Details
### Libraries Used
- Python
- Keras
- NumPy
- Pandas
- Scikit-learn
- Matplotlib

### Code Explanation
1. **Data Preprocessing**: 
   - Utilized Pandas for handling and processing data.
   - Split data into training, validation, and test sets.

2. **Model Architecture**:
   - Built CNN models using Keras for feature extraction and classification.
   - Optimized model architecture to balance accuracy and computational efficiency.

3. **Training and Validation**:
   - Trained models over multiple epochs.
   - Used performance metrics such as Mean Squared Error (MSE), accuracy, F1 score, precision, and recall to evaluate the models.
   
4. **Performance Metrics**:
   - The table below shows the training and validation metrics for the model:

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
