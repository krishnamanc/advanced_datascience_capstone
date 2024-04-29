This Capstone project, part of the IBM Advanced Data Science Specialization, focuses on Auto Insurance Claims Fraud Detection. You can explore the project in detail through this [YouTube video](https://www.youtube.com).

Key aspects of the project include:

- Utilizing a structured and repeatable process for Data Science projects, covering Initial Data Exploration, Extract, Transform, Load (ETL), Feature Creation, Model Definition, Training, Evaluation, and Deployment.
- Employing Hyperparameter tuning and neural network architecture tuning using `talos`.
- Creating atomic assets and documenting architectural decisions for repeatability and reuse.

The work is organized into five notebooks, each focusing on a distinct phase of the data science process:

1) Exploratory Data Analysis (EDA) involves identifying quality issues, assessing feature relevance, and understanding value distributions.
2) Data cleansing (ETL) covers aspects like data types, ranges, emptiness, uniqueness, and regular expressions.
3) Feature Creation includes imputing, scaling, filtering, and discretizing features.
4) Model Definition, Training, Evaluation, and Comparison encompass choosing performance indicators, evaluating models, and analyzing feature importances.
5) Hyperparameter Tuning using `Talos` involves creating flexible Keras models, defining parameter spaces, running hyperparameter scans, and analyzing results.

An example of the hyperparameter space and network architecture options for exploration is provided, totaling 540,000 permutations.

The project addresses a fraud detection problem in the insurance industry using a Kaggle dataset containing 1000 claims from Q1 2015, where fraud claims are labeled with 1s.

You can access the Kaggle dataset [here](https://www.kaggle.com/buntyshah/auto-insurance-claims-data) and learn more about the Talos framework [here](https://github.com/autonomio/talos).
