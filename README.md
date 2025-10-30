# Tkinter-HousingPricePrediction

A machine learning model with a Tkinter-based graphical interface for predicting house prices using key property features.  
This project integrates data analysis, model training, and an interactive desktop GUI for Windows users.

---

## Overview

This project demonstrates how machine learning and GUI development can work together to create a simple, user-friendly **House Price Prediction App**.  
It uses a regression model trained on housing data and provides a Tkinter interface that allows users to input house parameters (such as area, number of rooms, and location) to receive a price prediction.

---

## Features

- Machine learning model trained using `scikit-learn` on a structured housing dataset  
- Tkinter GUI for easy input and real-time prediction  
- Data analysis with `pandas` and `matplotlib`  
- Fully offline local execution  
- Modular structure with separate notebooks for training and the GUI app  

---

## Project Structure

Tkinter-HousingPricePrediction/
│
├── Housing.csv              # Dataset used for model training
├── HouseRegPred.ipynb       # Notebook for data analysis and model training
├── app_tkinter.ipynb        # Tkinter GUI application notebook
├── README.md                # Project documentation
└── requirements.txt         # Python dependencies


---

## Installation

**Requirements:**
- Windows OS  
- Python 3.8+  
- IDE (e.g., Jupyter Notebook, VS Code, PyCharm)

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Tkinter-HousingPricePrediction.git
`cd Tkinter-HousingPricePrediction`

### 2. Install Dependencies

pip install pandas numpy matplotlib scikit-learn tkinter
Note: tkinter is pre-installed with most Python distributions on Windows.

Usage
Step 1: Train the Model

Open HouseRegPred.ipynb in Jupyter Notebook or your preferred IDE and run all cells.
This will:

Load and preprocess the dataset (Housing.csv)

Train a regression model

Evaluate its performance

You may export or save the trained model using pickle or joblib.

Step 2: Launch the Tkinter App

Open app_tkinter.ipynb and run it.
A GUI window will appear, allowing you to:

Enter property details (features)

Click Predict

View the estimated price on the screen

Tools and Technologies
Category	Tools Used
Programming Language	Python
Libraries	Pandas, NumPy, Matplotlib, Scikit-learn, Tkinter
Environment	Jupyter Notebook / Local IDE
OS Compatibility	Windows only

Author
Ebenezer Nortey

You are welcome to contribute or open issues for improvements.

License

None. This project is shared for educational and personal learning purposes.

Acknowledgments

Special thanks to the open-source community and the developers of the libraries used in this project.