# Task2
# Titanic Dataset Analysis

This project explores the famous [Titanic Dataset](https://www.kaggle.com/c/titanic/data) using Python, covering end-to-end data preprocessing, visualization, and feature-level analysis.

## Technologies Used

- Python 
- NumPy & Pandas
- Seaborn & Matplotlib
- Statistics module

### Encoding:
- Converted categorical features (`Sex`, `Embarked`, etc.) to numeric using `LabelEncoder`.

### Normalization:
- Standardized numerical columns (`Age`, `Fare`) using Z-score normalization via `StandardScaler`.

### Outlier Detection & Removal:
- Used boxplots to detect outliers in `Fare` and `Age`.
- Removed rows with extreme values using IQR method.



## Exploratory Data Analysis (EDA)

###  Visualizations:
- **Countplots** of survival by `Sex`, `Pclass`, `Embarked`
- **Histograms** & **KDE plots** for `Age`, `Fare`
- **Boxplots** to identify outliers
- **Pairplot** and **Correlation Matrix** to explore relationships between features

###  Summary Statistics:
- Computed `mean`, `median`, `std`, `min`, `max` using both `numpy` and `statistics` modules.


##  Key Feature-Level Inferences

| Feature     | Insight |
|-------------|---------|
| **Sex**     | Females had much higher survival rates |
| **Pclass**  | 1st class passengers survived more |
| **Age**     | Children under 10 had better chances |
| **Fare**    | Higher fare correlates with higher survival |
| **Embarked**| Port 'C' had more survivors |
| **SibSp/Parch** | 1–2 family members helped survival; too many hurt it |



