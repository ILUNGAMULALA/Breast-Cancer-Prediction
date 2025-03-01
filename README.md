# Breast Cancer Predictor

## Overview

This project is a **Breast Cancer Prediction** web application built using **Streamlit**, **Pandas**, **Plotly**, and **Scikit-learn**. It allows users to input cell nuclei measurements and predicts whether a breast tissue sample is benign or malignant using a trained machine learning model.

## Features

- **Interactive Sidebar**: Users can input cell nuclei details using sliders.
- **Radar Chart Visualization**: Displays the mean, standard error, and worst values for key cell characteristics.
- **Machine Learning Prediction**: Uses a pre-trained model to classify breast cancer samples as benign or malignant.
- **Probability Display**: Shows the likelihood of each classification.
- **User-friendly UI**: Simple and intuitive interface designed for use in cytology labs.

## Installation

### Prerequisites

Ensure you have Python installed. Recommended version: **Python 3.7+**.

### Clone the Repository

```bash
git clone https://github.com/your-username/breast-cancer-predictor.git
cd breast-cancer-predictor
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

## Running the Application

```bash
streamlit run app.py
```

## File Structure

```
├── data/
│   ├── data.csv  # Dataset used for model training and prediction
├── model/
│   ├── model.pkl  # Trained machine learning model
│   ├── scaler.pkl # Scaler for feature normalization
├── assets/
│   ├── style.css  # Custom styles for the UI
├── app.py         # Main application script
├── requirements.txt # Required Python packages
├── README.md      # Project documentation
```

## Usage

1. Run the application and navigate to the provided **local URL**.
2. Adjust the **cell nuclei measurements** using the sliders in the sidebar.
3. View the **Radar Chart** to compare feature values.
4. The model will predict whether the sample is **Benign** or **Malignant** along with probabilities.

## Technologies Used

- **Python**
- **Streamlit**
- **Pandas**
- **Scikit-learn**
- **Plotly**
- **NumPy**

## Disclaimer

This application is designed as an **assistive tool for medical professionals** and should **not** be used as a substitute for professional medical diagnosis.

## License

This project is licensed under the MIT License.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

---

### Author
I give credit to:
[Your Name](https://github.com/alejandro-ao)
Thank you for your 2 hours class.

