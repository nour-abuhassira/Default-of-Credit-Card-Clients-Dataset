# Default of Credit Card Clients - Data Cleaning & Predictive Modeling

This project covers the full data science lifecycle of the "Default of Credit Card Clients" dataset—from raw data cleaning to building and evaluating predictive models.

## Project Overview
The goal is to predict the likelihood of a client defaulting on their credit card payment. This project is divided into two phases: preparing the data and implementing machine learning algorithms to identify high-risk customers.

---

## Project Structure

### [Part 1: Data Cleaning & Preprocessing]
The first notebook focuses on data quality and consistency:
* **Handlying missing values:** categorical attributes are filled with their most frequent category and numerical attributes are replaced with the mean of the column.
* **Outlier dedection and removal:** Extreme or unrealistic values are identified using the Z-score method.
* **Normalization and scaling:** Continuous numerical variables(e.g., credit limit, bill amounts, age) are normalised using statistical formulas to make them comparable in scale.
* **Data smoothing:** Sequential financial variables (bill and payment history) are smoothed to reduce irregular fluctuations.
* **Visualization and insight extraction:** Visual exploration highlights how factors like payment delay, education level, or credit limit relate to the probability of default.
  
### [Part 2: Advanced Cleaning & Model Building]
The second notebook moves from preparation to prediction:
* **Advanced Preprocessing:** Finalizing feature transformations and handling payment history inconsistencies.
* **Model Implementation:** Building machine learning models to predict defaults.
* **Performance Evaluation:** Analyzing model accuracy and results and compareit to determine how well the variables (like billing history and demographics) predict financial risk.

---

## Dataset Variables
The dataset includes 25 variables such as:
- **Demographics:** Gender, Education, Marital Status, Age.
- **Financials:** Amount of given credit, monthly bill statements, and previous payment amounts.
- **History:** Past payment tracking from April to September.
- **Target:** `default.payment.next.month`.

---

## Getting Started

### Prerequisites
- Python 3.x
- Pandas
- Numpy
- Matplotlib / Seaborn

### How to Run

To replicate the results, follow these steps in order:

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/nour-abuhassira/Default-of-Credit-Card-Clients-Dataset.git](https://github.com/nour-abuhassira/Default-of-Credit-Card-Clients-Dataset.git)
   cd Default-of-Credit-Card-Clients-Dataset
2. Install Required Libraries:
    pip install pandas numpy matplotlib seaborn scikit-learn
3. Step 1 - Data Cleaning: Open and run 'Default of Credit Card Clients Dataset_cleaning.ipynb' to generate the cleaned baseline of the dataset.
4. Step 2 - Modeling: Open and run 'Default of Credit Card Clients Dataset_cleaning_part2.ipynb' to see the advanced processing and the final Machine Learning model results.
  
