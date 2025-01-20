
# Insurance Claim Prediction using Machine Learning

## Project Overview
This project focuses on predicting whether a policyholder will make an insurance claim based on various demographic and health factors such as age, gender, BMI, number of children, smoking status, and medical costs.

### Dataset Description
The dataset includes the following features:

- **age**: Age of the policyholder.
- **sex**: Gender of the policyholder (Male = 1, Female = 0).
- **bmi**: Body Mass Index, indicating the policyholder's physical condition.
- **children**: Number of children or dependents.
- **smoker**: Whether the policyholder is a smoker (Yes = 1, No = 0).
- **region**: Region where the policyholder resides (Northeast = 0, Northwest = 1, Southeast = 2, Southwest = 3).
- **charges**: Medical costs billed to the policyholder.
- **insuranceclaim**: Whether an insurance claim was made (Yes = 1, No = 0).

### Objective
The primary goal of this project is to build a machine learning model that predicts whether an insurance claim will be made based on the above features.

## Project Structure
- **Insurance_Claim_Prediction_using_ML.ipynb**: The Jupyter notebook containing the full data analysis and machine learning pipeline.
- **README.md**: This file that explains the project and provides guidance on how to run the notebook.

## Requirements
To run the notebook, you will need the following libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install the required libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## How to Run
1. Download the dataset and ensure it is available in the same directory as the notebook.
2. Open the `Insurance_Claim_Prediction_using_ML.ipynb` notebook in Jupyter or any other notebook environment.
3. Follow the steps outlined in the notebook to preprocess the data, train the model, and evaluate the results.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Acknowledgements
The dataset used in this project was provided for educational purposes to demonstrate the application of machine learning in predicting insurance claims.
