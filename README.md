# NBA-Game-Predictor
Predicting NBA 2024–2025 season games using machine learning

# NBA Game Predictor (2024–2025)

This project predicts NBA game outcomes for the 2024–2025 season using a combination of traditional machine learning and deep learning techniques. It simulates how an NBA front office might use statistical trends and recent team performance to forecast wins.

## Project Overview

The project is built around a binary classification task: predicting whether the home team will win (1) or lose (0). The model uses features such as:

- Home vs Away team rating difference  
- Win streak difference  
- Home court advantage

## Tools and Techniques

- Python / NumPy / Pandas for data simulation and preprocessing  
- Scikit-learn for Logistic Regression and Random Forest  
- TensorFlow / Keras for LSTM sequence model  
- Matplotlib (optional) for future visualizations

## Models Used

- Logistic Regression (Baseline)  
- Random Forest (Baseline)  
- LSTM Sequence Model (Deep Learning)

The LSTM model outperforms the others by modeling recent form through a rolling window of past 10 games.

## Results

| Model              | Accuracy |
|-------------------|----------|
| Logistic Regression | ~50–55% |
| Random Forest       | ~55–60% |
| LSTM (Deep Learning)| ~65–70% |

All models were trained and tested on simulated NBA data. LSTM’s use of game sequences made it the most effective.

## Files

- `NBA_Game_Predictor_RealTime_2024_2025_FIXED.ipynb`: Final Jupyter Notebook  
- `README.md`: Project overview and explanation

## Future Work

- Integrate real NBA data from the 2023–2024 season  
- Add PostgreSQL backend to store team and game data  
- Visualize prediction confidence and historical patterns  
- Build a web interface using Flask or Streamlit

Feel free to fork or explore this project if you're interested in sports analytics or machine learning with time series data.
