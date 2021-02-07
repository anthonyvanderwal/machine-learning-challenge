# machine-learning-challenge
UWA Boot Camp Data Analytics - homework assignment 21 - Machine Learning - Exoplanets

# machine-learning-challenge
- UWA Boot Camp Data Analytics
- Homework Assignment 21 - Machine Learning - Classification of Exoplanets
- [Anthony van der Wal](https://anthonyvanderwal.github.io/my-first.html) - 13 February 2021.
<br><br>

---
### Exoplanet Classification - Support Vector Classification (SVC) Model
- [notebook](./model1_svc.ipynb/) with data engineering and model optimisation.
- [model](./analysis/anthony_vanderwal_svc.sav) with the 'optimum' parameters from a grid search.
- [confusion matrix](./analysis/anthony_vanderwal_svc.png) of test dataset.

---
### Exoplanet Classification - Logistic Regression Model
- [notebook](./model2_logreg.ipynb/) with data engineering and model optimisation.
- [model](./analysis/anthony_vanderwal_logreg.sav) with the 'optimum' parameters from a grid search.
- [confusion matrix](./analysis/anthony_vanderwal_logreg.png) of test dataset.


---
### Summary
- Data engineering included dropping meaningless features (right ascension and declination), scaling (MinMaxScaler), and selection (reduce features by 50% using SelectKBest with chi2 criteria).
- Both models exhibited improved accuracy (approx. 4 percentage points) with parameter fine tuning using the GridSearchCV module.
- There are only marginal differences between the models' performance when subjected to the test dataset.
