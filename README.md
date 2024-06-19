# Machine Learning Repository Overview

## Model Directory

The `Model/` directory contains files related to the trained machine learning model.

- **best_model.h5**: Trained model saved in HDF5 format, representing the final product of the scripts.
  
- **model_json/**: Directory containing the TensorFlow.js conversion of the model.

  - **model.json**: Architecture and weights of the model converted to TensorFlow.js format.

## Scripts Directory

The `Scripts/` directory includes Jupyter Notebooks used for model development and testing.

- **Scripts.ipynb**: Notebook with scripts for building and training the machine learning model.
  
- **Test.ipynb**: Notebook containing scripts for testing the trained model's performance and functionality.

## Usage

1. **Clone the Repository**:
   ```bash
   git https://github.com/cataract-bangkit/machine-learning.git
   cd machine-learning
   ```
   
2. **Model Training**:
- Upload Scripts.ipynb to Google Colab and execute the notebook to build and train the model using the provided datasets and parameters.


3. **Model Testing**:
- Upload Test.ipynb to Google Colab and execute the notebook to load the trained model and evaluate its performance on test data.
