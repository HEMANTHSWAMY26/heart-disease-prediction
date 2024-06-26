# Heart Disease Prediction

This project is a heart disease prediction system built using the KNeighborsClassifier algorithm. The system takes user input for various medical attributes and predicts the likelihood of heart disease.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Model Training](#model-training)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Heart disease is a leading cause of death worldwide, and early detection is crucial for effective treatment and management. This project aims to provide an easy-to-use web application that predicts the presence of heart disease based on user-provided medical data.

## Features

- **Web Interface**: A simple web interface to input medical data and get predictions.
- **Model**: Uses KNeighborsClassifier for prediction.
- **Visualization**: Displays the prediction result with a heart animation.

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/HEMANTHSWAMY26/Heart-Disease-Prediction.git
    cd Heart-Disease-Prediction
    ```

2. **Create and activate a virtual environment**:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. **Install the required packages**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Flask application**:
    ```bash
    python app.py
    ```

## Usage

1. Open your web browser and go to `http://127.0.0.1:5000/`.
2. Enter the required medical details in the form.
3. Click on the "Predict" button to get the prediction result.

## Model Training

The model is trained on the heart disease dataset (`heart.csv`). The following attributes are used for prediction:

- `age`: Age of the patient
- `sex`: Sex of the patient (1 = male; 0 = female)
- `cp`: Chest pain type (0-3)
- `trestbps`: Resting blood pressure (in mm Hg)
- `chol`: Serum cholesterol in mg/dl
- `fbs`: Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
- `restecg`: Resting electrocardiographic results (0-2)
- `thalach`: Maximum heart rate achieved
- `exang`: Exercise induced angina (1 = yes; 0 = no)
- `oldpeak`: ST depression induced by exercise relative to rest
- `slope`: The slope of the peak exercise ST segment (0-2)
- `ca`: Number of major vessels (0-3) colored by fluoroscopy
- `thal`: Thalassemia (1 = normal; 2 = fixed defect; 3 = reversible defect)

## Results

The prediction result will be displayed on the result page with a message indicating the likelihood of heart disease. The heart animation will visually represent the result.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
