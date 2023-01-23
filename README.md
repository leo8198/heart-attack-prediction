# Heart-attack prediction using ML
Heart attack prediction using machine learning algorithms and pre-processing data

It's a binary classification problem (0 and 1) where for 1 the patient had a heart attack and for 0 he didn't. The dataset used was the [heart attack dataset from UC Irvine](https://archive.ics.uci.edu/ml/datasets/heart+disease). The data contains 303 samples.
<br>


My final model achieved **81% of accuracy**.
<br>

### Pre-processing

- Exploratory Data Analysis (EDA)
- Separate between train and test data
- Removing null values
- Removing outliers through boxplot
- Normalizing data
- PCA analysis
- Analyse the correlation matrix
<br>

### Machine learning algorithms

- Dummy classifier (week baseline)
- Random Forest
- XGBoost
- Naive Bayes
- Logistic Regression
- Support Vector Machines
<br>

### Metrics
Applied the following metrics to analyse the models results:

- Accuracy
- ROC Curve
- F1 Score


The best algorithm was Random Forest with 79% of accuracy.
<br>

### Fine-tuning

- Random Grid search
- Cross-validation

The fine-tuned model improved the accuracy to 81%. Other papers achieved around 80% of accuracy as well. 
<br>

### Possible improvements

- Aggregate patients data like age by range instead of raw numbers
- Test removing variables with 0.40 correlation
- Use log(x) for the "caa" variable to normalize the data distribution
- Use other algorithms like Catboost
- Tune XGBoost hyperparameters


