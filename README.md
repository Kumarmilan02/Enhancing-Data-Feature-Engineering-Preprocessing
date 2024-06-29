# Feature Engineering & Data Preprocessing

This repository demonstrates feature engineering, data preprocessing techniques, and outlier detection using Python and popular machine learning datasets (`titanic.csv` and `application_train.csv`).

## Overview

Feature engineering and data preprocessing are critical steps in preparing data for machine learning models. These processes involve transforming raw data into meaningful features that enhance model performance. Outlier detection is also crucial to ensure data quality and model robustness.

## Datasets

### Titanic Dataset (`titanic.csv`)

- Dataset containing passenger information from the Titanic disaster.
- Used for exploratory data analysis (EDA), feature engineering, and predictive modeling.

### Application Train Dataset (`application_train.csv`)

- Dataset related to loan applications, including financial and personal attributes of applicants.
- Utilized for predictive modeling tasks to predict loan approval outcomes.

## Methods Used

### Feature Engineering

- **Handling Missing Data**: Imputation techniques such as mean, median, or mode.
- **Creating New Features**: Derived features like family size, fare per person, and categorical transformations (e.g., age groups, title extraction).
- **Encoding Categorical Variables**: Conversion of categorical variables into numerical formats suitable for machine learning algorithms.

### Outlier Detection

- **Boxplot Analysis**: Visualizing outliers in single-variable distributions using boxplots and IQR thresholds.
- **Local Outlier Factor (LOF)**: Algorithm used for detecting outliers in multivariate datasets by calculating local density deviations.

## Usage

To replicate the analysis:

1. Clone the repository.
2. Install necessary Python libraries (`pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`).
3. Explore `data_preprocessing.ipynb` to see detailed implementations of feature engineering, data preprocessing, and outlier detection techniques.
4. Adapt the code for your datasets or extend the analysis based on your requirements.

## Results

- Demonstrated effective methods for feature engineering, handling missing data, and encoding categorical variables.
- Identified outliers using visualizations and algorithms like LOF, ensuring data quality and model reliability.

## Contributions

Contributions are welcome to enhance feature engineering techniques, improve outlier detection methods, or explore additional datasets. Please fork the repository and submit pull requests with your changes.

## References

- [Feature Engineering & Data Preprocessing by Deniz Gunay](https://medium.com/@denizgunay/feature-engineering-data-preprocessing-d6bc219b6b93)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


