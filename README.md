# Athlete Classification Project

This project explores how we can use basic health and lifestyle data to predict whether a person is likely to be an athlete.  
I built and tested the model entirely in Google Colab using synthetic (but realistic) data for 200 individuals.

---

## Input Features

The model is trained using the following features:
- Height (in centimeters)
- Weight (in kilograms)
- Age
- Average sleep duration (hours/day)
- Number of workout days per week
- Daily calorie intake
- Estimated body fat percentage

---

## Machine Learning Model

- **Type:** Logistic Regression  
- **Library:** Scikit-learn (`sklearn`)  
- **Goal:** Binary classification — is the person an athlete or not?  
- **Accuracy achieved:** ~90%  
  *(note: slight class imbalance in the data)*

---

## What This Project Demonstrates

- End-to-end pipeline: data generation → labeling → training → evaluation
- Feature selection and labeling logic based on health & fitness reasoning
- Use of Python libraries like Pandas, NumPy, and Scikit-learn
- Practical application of classification for real-world-like decision making

---

## Files

- `athlete_classifier_project.ipynb` — Complete notebook with code, comments, and evaluation output

---

## Author

Created by **Omid Akbarian**  
Google Colab | Python | Machine Learning Foundations
