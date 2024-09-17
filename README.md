
# Titanic Survival Prediction with Neural Networks

## Project Overview
This project involves building neural network models to predict the survival of passengers on the Titanic. It builds on lessons learned from a previous attempt for a Kaggle competition, specifically from a feature engineering perspective. This version differs in its focus on neural network architectures and optimisation techniques.

## Key Skills and Techniques
- **Exploratory Data Analysis:** In-depth data cleaning, feature engineering, and visualisation.
- **Model Training:** Built neural network models using TensorFlow's Sequential API.
- **Optimisation:** Compared model performance with different optimisers (Adam, RMSProp).
- **Regularisation:** Implemented L2 regularisation and dropout to prevent overfitting.
- **Early Stopping:** Used early stopping to enhance computational efficiency.
- **Evaluation Metrics:** Used accuracy, loss plots, and visualisations for model comparison.
- **Libraries:** `TensorFlow`, `Keras`, `pandas`, `scikit-learn`, `matplotlib`, `seaborn`.

## Results & Lessons Learned
- **Optimal Configuration:** Found that early stopping and an appropriate balance of regularisation techniques improved model performance and computational efficiency.
- **Performance Comparison:** While both Adam and RMSProp optimisers achieved similar results, the Adam optimiser provided slightly more consistent accuracy across multiple runs.
  
## Usage
Refer to the notebook for the complete analysis, including data preprocessing, model building, optimisation, and evaluation.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.
