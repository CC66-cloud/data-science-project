# Titanic Data Analysis Project

## 1. Research question
What factors (such as gender and passenger class) were most strongly associated with passenger survival on the Titanic?

## 2. Dataset source and permissions
The dataset used is the public "Titanic - Machine Learning from Disaster" dataset, provided by Pranav Sharma on Kaggle. 
- **Source link:** https://www.kaggle.com/datasets/ps23122005/titanic-machine-learning-from-disaster
- **Permissions:** As a public Kaggle dataset intended for educational and machine learning practice, it is freely available for use.

## 3. Methods and tools
I used Python, pandas, and Seaborn/Matplotlib to inspect the data, handle missing values, calculate descriptive statistics, and compare survival distributions.
**Data Cleaning steps:** 
- Filled missing values in the `Embarked` column with the mode.
- Dropped the `Cabin` column due to a high number of missing values (687 out of 891).
- Filled missing values in the `Age` column (177 missing values).

## 4. Key findings
Based on the visual analysis, both gender and passenger class significantly impacted survival rates:
- **Gender:** Female passengers had a significantly higher survival rate (approximately 74%) compared to male passengers (approximately 19%).
- **Passenger Class:** Passengers in 1st class had the highest survival rate (over 60%), followed by 2nd class (around 47%), while 3rd class passengers had the lowest survival rate (around 24%).

## 5. Limitation
This analysis describes the provided sample dataset and identifies correlations. It does not establish causal relationships, nor does it guarantee that the same patterns occur in all populations or real-world scenarios outside this specific historical dataset. Additionally, dropping the `Cabin` column may have removed potentially useful spatial information.

## 6. Reproduction instructions
To run this analysis locally:
1. Ensure you have Python installed.
2. Clone this repository to your local machine.
3. Install the required dependencies by running: `pip install -r requirements.txt`
4. Ensure the dataset file (`train.csv`) is in the same directory as the notebook.
5. Open the `Titanic analysis.ipynb` file using Jupyter Notebook and run all cells.
