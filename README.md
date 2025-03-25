# mlb-betting-predictions
# MLB Betting Predictions App

This is a Streamlit-based application that leverages machine learning models to predict the outcomes of MLB games. The app uses a Random Forest Classifier to predict the **Moneyline** (home team win probability) and a Random Forest Regressor to predict the **Total Runs** for each game.

## Features

- **Moneyline Prediction**: Predicts the probability of the home team winning based on game features such as Elo ratings, pitcher ratings, and more.
- **Total Runs Prediction**: Predicts the total number of runs scored in the game, offering insights into whether the total runs will be over or under a specified value.
- **Interactive UI**: Users can select the home and away teams, choose a game date, and receive predictions for Moneyline and Total Runs.
- **Visualizations**: The app provides feature importance charts and visualizations comparing predicted vs. actual total runs.

## Requirements

To run the app locally, you will need the following Python packages:

- `streamlit`
- `scikit-learn`
- `pandas`
- `numpy`
- `matplotlib`

These dependencies can be installed using `pip` from the `requirements.txt` file:

```bash
pip install -r requirements.txt
How to Run Locally
Clone this repository to your local machine:

bash
Copy
Edit
git clone https://github.com/bethwelbruce/mlb-betting-predictions.git
Navigate to the project directory:

bash
Copy
Edit
cd mlb-betting-predictions
Install the required dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the Streamlit app:

bash
Copy
Edit
streamlit run app.py
The app will open in your browser at http://localhost:8501.

Deployment
The app is also deployed on Vercel, and you can access it online at:

MLB Betting Predictions App

Features to Come
Support for additional bet types (e.g., Over/Under).

Enhanced UI with more betting statistics.

Additional models and algorithms to improve predictions.

License
This project is licensed under the MIT License - see the LICENSE file for details.

markdown
Copy
Edit

### **Explanation**:
- **Introduction**: Provides a brief overview of the app and its functionality.
- **Features**: Highlights the key features of the app, such as predictions and visualizations.
- **Requirements**: Lists the necessary dependencies for running the app.
- **How to Run Locally**: Provides detailed steps for running the app on your local machine.
- **Deployment**: Links to the deployed version of the app on **Vercel**.
- **Features to Come**: Mentions any future improvements.
- **License**: Specifies the project's license (optional).

This should be ready to be copied and pasted into your **`README.md`** file.

Let me know if you need any modifications or additions!





