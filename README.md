# Google-Play-Store-App-Rating-Prediction ( Jupyter Notebook )
An end-to-end data analysis and machine learning project built in Jupyter Notebook to predict app ratings on the Google Play Store using real-world data.

## Dataset
Google Play Store dataset containing app details — Category, Reviews, Size, Installs, Type, Price, Content Rating, Genres, and Ratings.

## Libraries Used

-pandas, numpy — data manipulation and cleaning

-matplotlib, seaborn — data visualization

-scikit-learn — machine learning model

## Steps Performed
### 1. Data Cleaning

-Dropped rows with missing values in Rating, Reviews, Size, and Installs

-Converted Reviews, Installs, Price, and Size columns from string to numeric

-Removed special characters (commas, +, $, M, k) from columns

-Removed duplicate records

### 2. Exploratory Data Analysis (EDA)

-Distribution of App Ratings (Histogram + KDE)

-Top Categories by number of apps (Bar Chart)

-Free vs Paid Apps breakdown (Count Plot)

-Correlation between Reviews and Ratings (Scatter Plot)

-Price Distribution for Paid Apps (Histogram)

-Top 10 Genres by Total Installs (Bar Chart)

### 3. Machine Learning — Rating Prediction

-Encoded categorical variables using Label Encoder

-Defined features: Category, Reviews, Size, Installs, Type, Price, Content Rating

-Split data: 70% Train / 30% Test

-Trained a Random Forest Regressor (100 estimators)

-Evaluated model using MSE and R² Score

## Tools Used

-Python (Jupyter Notebook)

-pandas, numpy, matplotlib, seaborn, scikit-learn
