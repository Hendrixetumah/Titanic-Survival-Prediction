# Titanic Survival Prediction
An end-to-end ML project featuring data cleaning, feature engineering, and model training. Our optimized model achieves ~85% accuracy, providing insights into the key factors influencing passenger survival.


[![Python Version](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## Table of Contents
- [Overview](#overview)
- [Project Description](#project-description)
- [Installation Instructions](#installation-instructions)
- [Usage Examples](#usage-examples)
- [Key Outcomes](#key-outcomes)
- [Methodology](#methodology)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview

The **Titanic Survival Prediction** project is a machine learning initiative aimed at predicting whether a passenger would survive the Titanic disaster. By leveraging historical data and advanced modeling techniques, this project provides insights into the factors that influenced survival.

## Project Description

- **Purpose:**  
  The purpose of this project is to develop an accurate predictive model that can classify Titanic passengers as survivors 
  or non-survivors using historical data.

- **Goals:**  
  - Build and test several classification models.
  - Optimize model performance using techniques such as hyperparameter tuning and cross-validation.
  - Provide actionable insights into key predictive features (e.g., passenger class, age, gender).
  - Demonstrate data preprocessing, feature engineering, and model evaluation best practices.

- **Key Features:**  
  - **Data Cleaning:** Handling missing values, outlier detection, and feature transformation.
  - **Feature Engineering:** Creating new features (e.g., extracting titles from names, grouping ages).
  - **Modeling:** Implementation of logistic regression and other classification models.
  - **Evaluation:** Use of cross-validation, confusion matrices, and performance metrics like accuracy and AUC-ROC.
  - **Visualization:** Detailed plots for exploratory data analysis and model performance evaluation.

## Installation Instructions

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Hendrixetumah/Titanic-Survival-Prediction.git
   cd Titanic-Survival-Prediction
  
2. **Set Up a Virtual Environment (Optional but Recommended):**
    ```bash
   pip install -r requirements.txt
    
3. **Install Required Dependencies:**
   ```bash
   pip install -r requirements.txt
   #Ensure your requirements.txt includes packages such as pandas, numpy, scikit-learn, matplotlib, seaborn
   
4.**Download the Dataset:**
  Download the *train.csv* Titanic dataset from [kaggle competitions](https://www.kaggle.com/competitions/titanic/data)) 
  and place it in the data/ directory or update the paths in your code accordingly.

## Usage Examples
  <!--**Online Usage**-->
  You can run this project directly in your browser using Google Colab or Binder:

    + Binder:
    Click the Binder badge above or use this link:
    [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Hendrixetumah/Titanic-Survival-Prediction/main?urlpath=notebook%2FTitanic_Survival_Prediction_Model.ipynb)
    
  + Google Colab:
    Click the Colab badge above or use this link:
    [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Hendrixetumah/Titanic-Survival-Prediction/blob/main/notebooks/Titanic_Survival_Prediction_Model.ipynb)


  <!-- ** Note ** -->
  <!--Explore and posibly include Local Usage instructions -->
  
## Key Outcomes

- **Model Performance:**  
  The model achieved an accuracy of approximately **85%** on the test set.

- **Insights:**  
  - Key predictors include passenger class, gender, and fare.  
  - First-class passengers and females had significantly higher survival rates.

- **Future Enhancements:**  
  Further improvements will focus on advanced feature engineering and exploring ensemble methods.

## Methodology

- **Data Cleaning:**  
  - Handling missing values and outliers.  
  - Transforming features (e.g., log transformation for skewed data).

- **Feature Engineering:**  
  - Extracting titles from names.  
  - Categorizing age into groups (Child, Adult, Senior Adult).

- **Modeling:**  
  - Evaluating multiple classification models.  
  - Hyperparameter tuning using GridSearchCV.  
  - Final model training on the entire dataset for optimal performance.
    

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

Feel free to reach out if you have any questions or suggestions:

- **Email:** [hendrixetumah@gmail.com](mailto:hendrixetumah@gmail.com)
- **LinkedIn:** [https://www.linkedin.com/hendrixetumah](https://www.linkedin.com/in/hendrixetumah/)
- **GitHub:** [https://github.com/Hendrixetumah](https://github.com/Hendrixetumah)

*Thank you for checking out the Titanic Survival Prediction project!*



