# Ischemic Heart Disease Detection

This repository contains the code for the Ischemic Heart Disease Detection project. The main goal of this project is to develop a predictive model for detecting Ischemic Heart Disease based on various features.

## Files

- `Ischemic_detection.ipynb`: Jupyter Notebook file containing the Python code for the project.
- `ischemia.txt`: Text file containing the dataset used for training and testing.

## Project Overview

The `Ischemic_detection.ipynb` notebook provides the implementation for the Ischemic Heart Disease Detection project. It includes the following steps:

1. **Data Reading**: The dataset is read into the notebook.
2. **Data Preprocessing**: The data is preprocessed, including handling missing values and factorizing specific columns.
3. **Feature Visualization**: Histograms are plotted to visualize the distributions of selected features.
4. **Train-Test Split**: The data is split into training and testing sets.
5. **Addressing Class Imbalance**: Oversampling techniques are applied to solve the imbalance problem.
6. **Model Training**: Various ML methods are trained, and meta-parameters are tuned using cross-validation.
7. **Model Evaluation**: The trained models are evaluated, and performance metrics such as accuracy are reported.
8. **Result Visualization**: The features are visualized using scatter plots, and the results are displayed.

## Requirements

The project requires the following packages:

- numpy
- pandas
- sklearn
- scipy
- seaborn
- matplotlib
- imblearn

Make sure to install these packages before running the notebook.

## Usage

To run the project:

1. Clone or download this repository.
2. Open the `Ischemic_detection.ipynb` notebook in Jupyter Notebook.
3. Run each cell in the notebook to execute the code.
4. Customize the code as needed for your specific use case or dataset.

Please refer to the notebook for detailed implementation and explanations. If you have any questions or need further assistance, feel free to reach out.

## License

This project is licensed under the [MIT License](LICENSE).
