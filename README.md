#  California House Price Prediction

A beginner-friendly machine learning project that predicts housing prices in California using the **XGBoost regression model**.

This project is based on the **California Housing dataset** from `sklearn.datasets`, and includes full steps from data exploration to model evaluation.



##  Files Included

- `House_Price_Prediction.ipynb` — Jupyter notebook with all code.
- `README.md` — Project description.



##  Dataset Used

- **California Housing Dataset**  
  Provided by `sklearn.datasets.fetch_california_housing()`  
  It contains entries with features such as:
  - Median income
  - House age
  - Average rooms, bedrooms
  - Population
  - Latitude & longitude  
  And the target is **median house value**.



##  Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Google Colab



##  Workflow Overview

1. **Data Loading** — load the California housing dataset from sklearn.
2. **Data Exploration** — view structure, shape, summary stats, and correlations.
3. **Data Visualization** — plot a heatmap of feature correlations.
4. **Preprocessing** — split features (`X`) and target (`Y`), then train/test split.
5. **Model Training** — use `XGBRegressor` to train on the data.
6. **Model Evaluation** — compute R² score and Mean Absolute Error (MAE).
7. **Visualization** — plot actual vs predicted house prices.



##  How to Run

1. Clone the repo or download the notebook.
2. Open `House_Price_Prediction.ipynb` in [Google Colab](https://colab.research.google.com/) or Jupyter Notebook.
3. Run all cells — no dataset upload is needed (data is loaded using sklearn).



##  Sample Output

- **R² Score (train)**: ~0.95  
- **R² Score (test)**: ~0.84  
- Actual vs. predicted prices scatter plot included in the notebook.




