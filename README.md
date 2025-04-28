# Heart Health Manager

**[Hackathon Project for Hack::Peel 2022](https://devpost.com/software/heart-stroke-manager)**

Cardiovascular diseases are the leading cause of death globally. In response, we developed **Heart Health Manager**, a web application designed to help reduce the risk of heart disease using machine learning.

## Demo
Click below to see a demo of the app and our pitch for Hack::Peel 2022. Also check out our [devpost](https://devpost.com/software/heart-stroke-manager) for more info.

[![thumbnail](https://github.com/user-attachments/assets/79cc9e07-d60c-43a8-96cb-f8b95cf77fde)](https://youtu.be/HC0wK17l1-Q?si=cce1MsLOUwVN2WPJ)

## Key Features

- **Stroke Prediction Model:** Trained on Kaggle stroke data, our custom machine learning model uses Scikit Learn to predict stroke risk based on user inputs.
- **User Data Management:** A SQL database stores user information securely, ensuring efficient access and retrieval.
- **Web Interface:** It is built with HTML, CSS, and JavaScript and provides an intuitive and responsive front-end for users to interact with the application.

## Technologies Used

- **HTML, CSS, JS:** For designing the front end.
- **Machine Learning:** Custom stroke prediction model using data from Kaggle and trained with Scikit Learn.
- **SQL:** For organizing and storing user data.
- **Flask:** To integrate the machine learning model and database with the website's backend.

## Installation and Setup

### Prerequisites
- Python

### Steps to Run
1. Clone the repository.
2. Navigate to the project directory and run `main.py`:
   """
   python main.py
   """
3. Open a browser and visit: [http://127.0.0.1:5000/](http://127.0.0.1:5000/)
4. The home page of the Heart Health Manager web application should now be displayed.
