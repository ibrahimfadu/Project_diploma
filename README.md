# **Project Diploma**

## Description
A machine learning project designed to predict the rank cutoff for various colleges based on historical data from 2019 to 2023. The project leverages Ridge Regression to provide predictions and is built using Flask for web deployment.

---

## **Features**
- **Rank Prediction**: Predict college cutoff ranks for various branches.
- **Data Analysis**: Analyzes historical college data (2019–2023) for cutoff predictions.
- **Flask Web Application**: Interactive UI for users to input their data and receive predictions.
- **Model Evaluation**: Model accuracy evaluated with different metrics to ensure performance.

---

## **Installation**

### Prerequisites
- Python 3.x  
- pip (Python package installer)  

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/ibrahimfadu/Project_diploma.git
   ```
2. Navigate into the project directory:
   ```bash
   cd Project_diploma
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## **Usage**
1. Launch the Flask app:
   ```bash
   python app.py
   ```
2. Open a browser and go to:
   ```
   http://127.0.0.1:5000/
   ```
3. Enter the required inputs in the form to get predictions for the rank cutoff.

---

## **Technologies Used**
- **Python**  
- **Flask**  
- **Scikit-learn** (for Machine Learning)  
- **Pandas**  
- **NumPy**  
- **HTML/CSS** (for Web Interface)

---

## **Project Structure**
```
Project_diploma/
│
├── app.py                 # Main Flask application
├── model.py               # Model file (training and prediction)
├── templates/             # HTML files for Flask views
│   ├── index.html         # Home page
│   └── result.html        # Prediction result page
├── static/                # Static files (CSS, JS)
├── requirements.txt       # List of dependencies
└── README.md              # Project Documentation (this file)
```

---

## **Contributing**
Feel free to fork the project, create an issue, or submit a pull request. Contributions are always welcome!

---

## **License**
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## **Acknowledgements**
- Thanks to the open-source community for their continuous support in building machine learning tools and web development frameworks.

---
