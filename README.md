# Predicting Employee Attrition! 
A Supervised Machine Learning Project by [Kevin Glugar | Data Analyst](https://www.linkedin.com/in/kevin-glugar/)

## Problem Statement
In today's dynamic business landscape, retaining top talent has evolved into a pivotal challenge. Employee attrition (employees voluntarily or involuntarily quitting their jobs for unforeseen reasons) is a pressing concern for many businesses. It can result in substantial costs due to recruiting, training, and potential disruptions. To navigate this challenge, businesses are increasingly resorting to advanced analytical techniques to predict employee behavior. This project leverages the [IBM HR Analytics](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset) dataset, a rich repository comprising over 34 diverse features, to predict employee attrition. By understanding the primary drivers behind attrition and developing an accurate predictive model, businesses can take proactive measures to retain valuable employees and ensure organizational stability.

## Technical Highlights and Key Learnings
- **In-depth Data Exploration**:
  - Conducted a thorough exploratory data analysis to understand data distributions, relationships, and patterns.
  - Leveraged visualization libraries like `matplotlib` and `seaborn` to display the distribution of both categorical and discrete features.
  
- **Advanced Data Preprocessing**:
  - Demonstrated adeptness in data cleaning by transforming raw data, encoding categorical variables, and ensuring data consistency.
  - Tackled the often-overlooked challenge of class imbalance using `SMOTE` to oversample the minority class, ensuring a more balanced dataset for modeling.

- **Robust Model Implementation**:
  - Employed and fine-tuned a `LightGBM` model, showcasing expertise in model selection, implementation, and performance tuning.
  - Paid meticulous attention to prevent data leakage, ensuring genuine model performance metrics.

- **Feature Engineering & Selection**:
  - Proficiently employed feature selection techniques like the `Chi-Squared` test and `ANOVA` F-value to distill the most impactful features from the dataset.
  
- **Technologies and Libraries**: Delved deep into the Python ecosystem, utilizing libraries such as `Pandas`, `Scikit-Learn`, `LightGBM`, `Matplotlib`, `Seaborn`, `imblearn`, and more.

## Model Performance

The LightGBM model demonstrated robust performance across various metrics. Here's a breakdown:

| Metric | Score |
|--------|-------|
| **Accuracy** | 0.9037 |
| **AUC Score** | 0.9032 |
| **Average Accuracy (Cross-Validation)** | 0.9226 |

### Classification Report:

|  | Precision | Recall | F1-Score | Support |
|---|-----------|--------|----------|---------|
| **Class 0** | 0.91 | 0.91 | 0.91 | 183 |
| **Class 1** | 0.90 | 0.89 | 0.90 | 160 |
| **Macro Avg** | 0.90 | 0.90 | 0.90 | 343 |
| **Weighted Avg** | 0.90 | 0.90 | 0.90 | 343 |

This table showcases the precision, recall, and F1-Score for both classes, providing a comprehensive view of the model's performance across different facets of the dataset.

_Note: Due to inherent randomness in some machine learning processes, scores may vary slightly between runs._


## Dataset
Sourced from Kaggle.com, [The IBM's HR Analytic's](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset) dataset is a rich compilation of diverse employee metrics - from personal details to job roles, satisfaction levels, and performance metrics. With a mix of categorical, numerical, and textual data, it provides an intricate view into factors influencing employee attrition.

## Contribution & Feedback
As a data science enthusiast, I believe in continuous learning and improvement. I value feedback from industry professionals, recruiters, and fellow data scientists. Your insights can foster enhancements and lead to a more robust solution. Please don't hesitate to share your thoughts or collaborate for further refinements.

## License
This project is under the MIT License. Open for sharing, adaptation, and collaboration with proper attribution.
