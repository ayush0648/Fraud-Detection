# Fraud-Detection
This project implements a credit card fraud detection system using Principal Component Analysis (PCA) and Logistic Regression. The system is trained on a dataset containing transaction details to identify fraudulent transactions.

**Features**
- Data Preprocessing: Standardizes the features to have zero mean and unit variance.
- Model Training: Utilizes Logistic Regression to train the model on preprocessed data.
- Model Evaluation: Evaluates the model using accuracy and precision metrics.

**Dataset**

The dataset used for this project is creditcard.csv, which includes transaction details and a class label indicating whether a transaction is fraudulent.

**Installation**

To set up the project locally, follow these steps:

*Clone the repository:*

git clone https://github.com/ayush0648/Fraud-Detection.git
cd Fraud-Detection

*Install dependencies:*

pip install -r requirements.txt

*Ensure that the dataset file creditcard.csv is placed in the project directory.*
Dataset link: https://drive.google.com/drive/folders/1QR6NOM_fMfTvyIrMYrmfJNpbcNifamXV?usp=sharing

**Usage**

- The input is the creditcard.csv dataset containing transaction details.
- Run the model training script:
python code.py


**Limitations**
Dataset has a bad positive to negative ratio.

