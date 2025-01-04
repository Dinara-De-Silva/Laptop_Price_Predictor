# Laptop Price Prediction Model

## Overview
This project is a **laptop price prediction system** that predicts the price of a laptop based on user input requirements, such as:
- Brand
- OS Type
- Weight
- CPU Type
- GPU Type

The prediction model is built using the **Random Forest Regression** algorithm, ensuring accurate and reliable price estimations. The project combines machine learning for the prediction model and Flask for the web application interface.

---

## Features
- User-friendly interface for entering laptop specifications.
- Real-time price prediction based on the provided inputs.
- Efficient data preprocessing and model training using robust Python libraries.

---

## Libraries and Tools Used
### Machine Learning and Data Preprocessing
- **pandas**: For data manipulation and preprocessing.
- **scikit-learn**: For developing the Random Forest Regression model.

### Web Application
- **Flask**: To create a lightweight and flexible web application.

---

## Inspiration
This project was inspired by a YouTube tutorial series: [Laptop Price Prediction Playlist](https://youtube.com/playlist?list=PL495mke12zYBQjqBy-wUYh2LCAWSj4Ayn&si=LAO5CaBnese71zKe).

---

## How It Works
1. Users input laptop specifications via the web application.
2. The model processes the input using pre-trained data.
3. The system predicts the price of the laptop and displays it to the user.

---

## Setup and Installation
1. Clone the repository.
2. Install the required libraries:
   ```bash
   pip install pandas scikit-learn flask numpy
3. Run the Flask application.
   ```bash
   python app.py
4. Access the web application at http://localhost:5000
   
