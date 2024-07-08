# Wine_Quality_Prediction
redict the quality of wine based on its chemical properties using a Random Forest model. The dataset includes features such as acidity, residual sugar, chlorides, and alcohol content, which are used to train and evaluate the model to classify wine quality on a scale of 0 to 10.


# Wine Quality Prediction Project

This project aims to predict wine quality using a Random Forest model. The dataset includes various chemical properties of wine and a quality score.

## Dataset

The dataset consists of the following columns:
- `fixed acidity`: The amount of acid in the wine (g/dm³)
- `volatile acidity`: The amount of acetic acid in the wine (g/dm³)
- `citric acid`: The amount of citric acid in the wine (g/dm³)
- `residual sugar`: The amount of sugar remaining after fermentation (g/dm³)
- `chlorides`: The amount of chloride in the wine (g/dm³)
- `free sulfur dioxide`: The amount of free sulfur dioxide in the wine (mg/dm³)
- `total sulfur dioxide`: The total amount of sulfur dioxide in the wine (mg/dm³)
- `density`: The density of the wine (g/cm³)
- `pH`: The pH level of the wine
- `sulphates`: The amount of potassium sulphate in the wine (g/dm³)
- `alcohol`: The percentage of alcohol in the wine (%)
- `quality`: The quality score of the wine (scale of 0-10)

## Project Structure

- `data/`: Directory containing the dataset.
- `notebooks/`: Jupyter notebooks used for analysis and model training.
- `src/`: Source code for data processing, model training, and evaluation.
- `models/`: Directory to save trained models.
- `README.md`: Project documentation.

## Getting Started

### Prerequisites

- Python 3.7+
- Required packages listed in `requirements.txt`

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/wine-quality-prediction.git
    cd wine-quality-prediction
    ```

2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

### Usage

1. Preprocess the data and train the model:
    ```sh
    python src/train.py
    ```

2. Evaluate the model:
    ```sh
    python src/evaluate.py
    ```

### Example

You can find an example of the data preprocessing, training, and evaluation process in the Jupyter notebooks located in the `notebooks/` directory.

## Results

The trained Random Forest model achieves an accuracy of 93% on the test set. Detailed evaluation metrics and visualizations can be found in the `notebooks/` directory.


