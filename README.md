# Rail-Index-Prediction-Model

This project focuses on building a machine learning-based regression model to predict the **Ride Index (RI)** using track condition data such as **Vertical Ride Index (VRI)** and **Lateral Ride Index (LRI)**. Ride Index is a key indicator of track quality and passenger ride comfort used in Indian Railways as per the Permanent Way Manual.

## What is Ride Index?

Ride Index is a numeric measure derived from oscillation data collected using sensors mounted on coaches. It combines **vertical and lateral accelerations** caused by track irregularities. 

- **Low RI values** → smoother ride, track in good condition.
- **High RI values** → rough ride, track may need maintenance.

## Dataset

The dataset includes:
- **VRI (Vertical Ride Index)**
- **LRI (Lateral Ride Index)**
- **Distance, Time, and other derived features**

This data is used to compute and predict the **Ride Index** using machine learning models.

## Objective

To build and evaluate a regression model that can accurately predict the Ride Index given VRI and LRI data, enabling proactive maintenance and improved passenger experience.

## ML Techniques Used

- **Data Cleaning & Preprocessing**
- **Feature Engineering**
  - Time-based feature extraction
  - Moving averages and interaction terms
- **Modeling**
  - Random Forest Regressor
  - Grid Search / Randomized Search for hyperparameter tuning
- **Evaluation**
  - R² Score
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)

## Tools & Libraries

- Python (Pandas, NumPy)
- Scikit-learn
- Matplotlib & Seaborn for visualization
- Jupyter Notebooks / Colab

## Machine Learning Model

- Evaluation Metric: R² Score
- Final R² Score achieved: **0.96**

## License

This project was developed as part of a internship at CRIS (Centre for Railway Information Systems). Not an official CRIS product, This project is intended for educational and research purposes only.

## Author

Kavin Raam M | LinkedIn: linkedin.com/in/kavinraam
