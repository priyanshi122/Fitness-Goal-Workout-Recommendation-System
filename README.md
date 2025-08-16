#  Fitness Goal Workout Recommendation System  

This project is a **Machine Learning-based Workout Recommendation System** built using Python and scikit-learn.  
It takes user inputs (like gender, weight, height, age, hip size, and medical conditions) and recommends the best fitness goal and workout plan.  

---

##  Features  
- Accepts user inputs:  
  - Gender (Male/Female/Other)  
  - Weight (kg)  
  - Height (cm)  
  - Age  
  - Hip Size (inches)  
  - Medical Condition (None, Diabetes, Asthma, Hypertension, Heart Disease, PCOD)  
- Trains a **Decision Tree Classifier** for predicting fitness goals.  
- Custom handling for **medical conditions** (like PCOD, Diabetes, Heart Disease, etc.) with tailored workout plans.  
- Runs seamlessly in **Google Colab**.  

---

##  Installation  

Since this runs in **Google Colab**, no setup is required other than installing dependencies.  

```bash
pip install scikit-learn pandas numpy

```
---
## Usage

1. Open the Colab Notebook (workout_recommendation.ipynb).

2. Run all cells to train the model.

3. Enter your details when prompted.

4. Get your Recommended Goal & Workout Plan.

---
## Machine Learning Model

Algorithm: Decision Tree Classifier

Accuracy: ~33% (with small sample dataset, can be improved with more training data)

The model predicts goals like:

1. Weight Loss

2. Muscle Gain

3. Fitness
   
- Medical conditions override ML predictions to ensure safe workout suggestions.
---

## Future Improvements

- Increase dataset size for higher accuracy.

- Add more detailed body measurements (BMI, waist, chest, activity level).

- Create a web app using Flask/Django.

- Deploy as a mobile app for easy fitness tracking.

---
## Example: 
<img width="1819" height="321" alt="Screenshot 2025-08-16 190726" src="https://github.com/user-attachments/assets/73759755-b258-4da0-9092-be4407b00913" />

<img width="1799" height="317" alt="Screenshot 2025-08-16 191022" src="https://github.com/user-attachments/assets/c1febf4f-db42-4d50-b4a9-e1ca519985f7" />

---
## Author

Developed by Priyanshi Katiyare

