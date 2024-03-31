# LSTM based Soft-Sensor for Estimating Nitrate Concentration in Aquaponics Pond

## Abstract
In aquaponics, monitoring nitrate levels is crucial for aquatic and plant well-being. Traditional methods are costly and time-consuming. To address this, an LSTM-based soft sensor was developed. LSTM effectively models nitrate concentration changes in aquaponics, achieving a remarkable MSE of 0.00074 and an R-squared score of 0.98. This solution holds potential for commercial applications, benefiting aquaponics operations, supporting researchers, and enhancing sustainability.

## Overview
This project focuses on developing an LSTM-based soft-sensor for estimating nitrate concentration in aquaponics ponds. The soft sensor leverages deep learning techniques to provide accurate and real-time insights into nitrate levels, enabling better management of aquaponic systems.

## Key Features
- Utilization of LSTM neural network architecture for modeling temporal patterns in nitrate concentration changes.
- Extensive preprocessing of water quality data including cleaning, scaling, and feature engineering.
- Training the LSTM model on a diverse dataset collected from various aquaponics ponds.
- Evaluation of model performance using metrics such as Mean Squared Error (MSE), R-squared Score, and Mean Absolute Error (MAE).
- Visualization of model predictions, error distribution, and residuals for thorough analysis.

## Usage
To use the LSTM-based soft-sensor for estimating nitrate concentration in aquaponics ponds, follow these steps:
1. Prepare your water quality dataset, ensuring it includes relevant features and nitrate concentration measurements.
2. Preprocess the dataset by cleaning missing values, scaling features, and performing necessary transformations.
3. Split the preprocessed dataset into training and testing sets.
4. Train the LSTM model on the training data, adjusting hyperparameters as needed.
5. Evaluate the model's performance using appropriate metrics and visualizations.
6. Use the trained model to make predictions on new data, providing valuable insights into nitrate concentration dynamics in aquaponic systems.

## Dataset

The dataset used in this project can be found on Kaggle at the following link:

[Sensor-based Aquaponics Fish Pond Datasets](https://www.kaggle.com/datasets/ogbuokiriblessing/sensor-based-aquaponics-fish-pond-datasets)

This dataset provides sensor-based measurements from aquaponics fish ponds, including water quality features and nitrate concentration. It serves as the foundation for training and evaluating the LSTM-based soft-sensor model for estimating nitrate concentration in aquaponics ponds.


## Dependencies
- Python (>=3.6)
- TensorFlow (>=2.0)
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Seaborn

## Contributors
- Dharshan A
- Dr. U. Srinivasulu Reddy
- Purushottam Kumar
- Dr. S. Ravimaran

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgments
Special thanks to Dr. U. Srinivasulu Reddy Sir, Purushottam Kumar Sir, and Dr. S. Ravimaran Sir for their contributions and support.
