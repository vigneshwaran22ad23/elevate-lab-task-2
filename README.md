# Titanic Dataset - Exploratory Data Analysis (EDA)

Hi there!  
This project involves a complete exploratory data analysis of the famous Titanic dataset. The goal is to understand the data thoroughly using statistics and visuals before building any machine learning models.

---

## Project Objective

We aim to explore and analyze the Titanic dataset using Python tools like Pandas, Matplotlib, Seaborn, and Plotly.  
We will search for patterns, missing values, trends, correlations, and basic feature insights using charts and statistics.

---

## Tools & Libraries Used

- **Python 3**
- **Pandas** for data handling
- **Seaborn** for beautiful statistical plots
- **Matplotlib** for basic visualizations
- **Plotly (Optional)** for interactive charts

---

## Dataset Info

- **Dataset**: Titanic (from Seaborn library)
- **Total Rows**: 891 passengers
- **Total Columns**: 15 features
- **Includes**: Age, Gender, Ticket Class, Fare, Survival info, etc.

---

## EDA Steps Covered

- [x] Dataset loading and basic info
- [x] Shape, datatypes, null value check
- [x] Summary statistics (mean, median, std)
- [x] Value counts and unique values
- [x] Missing value heatmap
- [x] Histograms and Boxplots
- [x] Countplots with hue
- [x] Outlier detection
- [x] Correlation heatmap
- [x] Pairplot and Violinplot
- [x] Groupby insights (example: survival by gender/class)
- [x] Visual trend spotting

---

## Key Insights from Data

- **Women** had a much higher survival rate than **men**.
- People in **1st class** had better survival chances.
- Passengers who paid higher **fare** tended to survive more.
- Most passengers were aged between **20 and 40 years**.
- Some columns like **deck** had many missing values.
- Outliers are present in **fare** (for example, someone paid 512).

---

## Sample Visuals

You’ll find charts such as:

- Survival rate by gender
- Fare distribution with outliers
- Correlation matrix of numeric features
- Age and Fare trends

---

## How to Run This Project

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/titanic-eda.git
   cd titanic-eda
