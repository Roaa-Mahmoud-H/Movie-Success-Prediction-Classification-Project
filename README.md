## Movie Success Prediction and Classification
**About**

Predict movie revenue and classify films as Hit or Flop using machine learning on the TMDB dataset. This project includes exploratory data analysis (EDA), feature engineering, and building multiple regression & classification models to provide accurate predictions and insights into movie success factors.

 ## Project Structure

**data/ :** Contains CSV datasets.

**scripts/ :** Python scripts for data cleaning, EDA, feature engineering, and modeling.

**notebooks/ :** Optional Jupyter notebooks for experimentation.

**requirements.txt :** Python dependencies for running the project.

## Features

**Numeric features:** budget, revenue, runtime, popularity, vote_count

**Categorical features:** genres, cast, crew, production companies, languages

**Derived features:** profit calculation, main cast count, release year

**Encoded categorical features for machine learning models**

## Models

**Linear Regression:** Predict numeric values such as revenue, vote_average, and vote_count

**Logistic Regression:** Classify movies as Hit or Flop

**Stacked Model:** Uses regression predictions as features for classification models

 ## How to Run

**Clone the repository:**

git clone https://github.com/Roaa-Mahmoud-H/Movie-Success-Prediction-Classification-Project.git


**Navigate to the project folder:**

cd Movie-Success-Prediction-Classification-Project


**Install dependencies:**

pip install -r requirements.txt


Run scripts or notebooks as needed.

## Screenshots

<img width="1489" height="490" alt="image" src="https://github.com/user-attachments/assets/537a0172-bf45-4011-825f-2b8531cc09e8" />

<img width="616" height="590" alt="image" src="https://github.com/user-attachments/assets/ecd346ec-3933-4a95-b649-7ba32eccbe48" />

<img width="686" height="547" alt="image" src="https://github.com/user-attachments/assets/2d88d407-3ae9-4bfa-8f35-f43d52296767" />

<img width="859" height="616" alt="image" src="https://github.com/user-attachments/assets/7ab75bac-4e5d-4122-afcf-91a2e371a5e1" />

## License

This project is licensed under the MIT License – see the LICENSE file for details.

## Contributing

Feel free to fork this repository, make improvements, and submit pull requests.

## Credits

**TMDB dataset:** The Movie Database (TMDB)

**Python libraries:** pandas, numpy, scikit-learn, matplotlib, seaborn
