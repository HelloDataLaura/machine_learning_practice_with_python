# machine_learning_practice_with_python
Machine Learning practice using Python on the Titanic dataset from Kaggle
https://www.kaggle.com/competitions/titanic/data

This practice relys on looking for how many passengers survive on the Titanic using Python on Google Colab.
Few points to highlight:
- Nul values on 'age' column (around 19.7% of null values) were imputed with the mean before min-max-scaler method was applied
- Null values on 'cabin' column were not imputed as its percentage was high (around 77.1% of null values) and the data was not relevantto determine if passengers survived
- Null values on 'embarked' column (around 0.22% of null values) were imputed with the mode before OHE (One Hot Enconding) method was applied
