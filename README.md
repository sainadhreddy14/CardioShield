# CardioShield: AI-Powered Heart Disease Risk Prediction and Personalized Health Recommendations

CardioShield is a web-based application that uses machine learning to predict the likelihood of heart disease based on various medical parameters. The system employs multiple machine learning models to provide accurate predictions, risk assessments, and personalized health recommendations.

---

## Demo & Screenshots

Below are some screenshots demonstrating the main features and user interface of CardioShield:

### 1. User Registration Page
![User Registration]
<img width="1920" height="1080" alt="Screenshot 2025-07-18 092732" src="https://github.com/user-attachments/assets/94b1ae92-cf0c-4ee3-975f-08f5ba7b66e1" />

### 2. Heart Disease Prediction Form
![Prediction Form]

<img width="879" height="879" alt="Screenshot 2025-07-18 093011" src="https://github.com/user-attachments/assets/53b5a028-a73c-4dec-8377-2cc0ec6ea0c9" />

### 3. Prediction Results and Model Confidence
![Prediction Results]
<img width="1171" height="881" alt="Screenshot 2025-07-18 093058" src="https://github.com/user-attachments/assets/7127bb2d-fd26-4094-bcfb-c114b01486c6" />

### 4. Detailed Recommendations
![Recommendations]<img width="1169" height="850" alt="Screenshot 2025-07-18 093113" src="https://github.com/user-attachments/assets/e2b41d64-c761-4151-90f6-c992789427e4" />

---

## Features

- **User Authentication**
  - Secure login and registration system
  - Password encryption using SHA-256
  - Session management

- **Heart Disease Prediction**
  - Comprehensive medical data input form
  - Multiple machine learning models:
    - Logistic Regression
    - Support Vector Machine (SVM)
    - Decision Tree
    - Random Forest
    - K-Nearest Neighbors (KNN)
  - Real-time prediction results
  - Risk level assessment
  - Detailed interpretation and recommendations

- **Modern UI/UX**
  - Responsive design using Bootstrap
  - Medical-themed interface
  - Interactive forms with validation
  - Real-time feedback

## Technical Stack

- **Backend**
  - Python 3.12
  - Flask web framework
  - SQLite database
  - Scikit-learn for machine learning models

- **Frontend**
  - HTML5
  - Bootstrap 5
  - JavaScript
  - Font Awesome icons

## Project Structure

```
src/main/python/
├── app.py                 # Main Flask application
├── users.db              # SQLite database for user management
├── models/               # Machine learning models
│   ├── heart_disease_model.py
│   └── models/          # Trained model files
├── webapp/              # HTML templates
│   ├── login.html
│   ├── register.html
│   └── predict.html
├── static/              # Static files
│   └── images/         # Medical illustrations
└── data/               # Dataset
    └── heart_disease_data.csv
```

## Setup Instructions

1. **Prerequisites**
   - Python 3.12 or higher
   - pip (Python package manager)

2. **Installation**
   ```bash
   # Clone the repository
   git clone [repository-url]
   cd [repository-name]

   # Install required packages
   pip install -r requirements.txt
   ```

3. **Running the Application**
   ```bash
   # Start the Flask server
   python src/main/python/app.py
   ```

4. **Accessing the Application**
   - Open your web browser
   - Navigate to `http://localhost:5000`
   - Register a new account or login
   - Start making predictions

## Usage Guide

1. **Registration/Login**
   - Create a new account using the registration page
   - Login with your credentials

2. **Making Predictions**
   - Fill in the medical parameters:
     - Age, Sex, Chest Pain Type
     - Blood Pressure, Cholesterol
     - Blood Sugar, ECG Results
     - Heart Rate, Exercise-Induced Angina
     - ST Depression, Slope
     - Number of Major Vessels, Thalassemia
   - Submit the form to get predictions
   - View detailed results and recommendations

## Security Features

- Password hashing using SHA-256
- Session-based authentication
- Input validation and sanitization
- Secure database storage

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Dataset: UCI Heart Disease Dataset
- Icons: Font Awesome
- UI Framework: Bootstrap
- Machine Learning: Scikit-learn 
