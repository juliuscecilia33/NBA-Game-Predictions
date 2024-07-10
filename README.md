# NBA Game Prediction
Code that predicts NBA game outcomes using machine learning techniques. It utilizes historical game data sourced from the NBA API to train a RandomForestClassifier model. The model predicts whether a team will win or lose based on various features such as team ID, opponent team ID, average points per game, home game indicator, and last game result

https://medium.com/@juliuscecilia33/predicting-nba-game-results-using-machine-learning-and-python-6be209d6d165

## Tools and Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- NBA API
- Google Colab
- Jupyter Notebook
- Matplotlib
- Seaborn

## Features
- Data Collection: Fetches NBA game data using the NBA API, including team performances, game results, and matchups.
- Data Processing: Converts and preprocesses data into a format suitable for machine learning models. Includes datetime conversion, feature engineering, and encoding categorical variables.
- Model Training: Utilizes a RandomForestClassifier to train on historical game data. Evaluates model performance using metrics such as accuracy, precision, recall, and F1-score.
- Prediction: Makes predictions on new matchups to assess the likelihood of team victories.
- Visualization: Visualizes data trends and model insights using Matplotlib and Seaborn.

##  How to Use

Setup Environment:
Install required libraries using pip install -r requirements.txt.


