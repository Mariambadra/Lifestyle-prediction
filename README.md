# Predicting Lifestyle Choices

## Project Documentation

In this project, we analyze a dataset of 475,675 records with 29 features, occupying approximately 112.5+ MB of memory. The dataset consists of 6 categorical and 23 numerical features, including:

- **Demographic**: Age, Gender, Location
- **Financial**: Financial wellness indices, Environmental awareness ratings
- **Personal Routine**: Average Weekly Exercise Hours, Average Daily Screen Time

Our target variable is **"Lifestyle Choice"**, a categorical feature, making this a classification task.

---

## Project Design

### Objectives
- Predict lifestyle choices based on various features.
- Analyze relationships between different variables and lifestyle choices.

### Features
- **Input Features**: Gender, Age, Annual Vacation Days, Average Monthly Spend on Entertainment, Number of Online Purchases, etc.
- **Output Feature**: Lifestyle Choice (categorical variable).

---

## Methodology

1. **Data Preprocessing**: Clean and preprocess the dataset to handle missing values and convert categorical variables into numerical formats.
2. **Exploratory Data Analysis (EDA)**: Visualize the data to understand distributions and relationships among variables.
3. **Model Selection**: Choose appropriate machine learning algorithms (e.g., Logistic Regression, Decision Trees, Random Forests) for classification.
4. **Model Training and Evaluation**: Split the dataset into training and testing sets, train the model, and evaluate performance using metrics like accuracy, precision, and recall.

---

## Model

### Selected Algorithms
- **Logistic Regression**: For binary classification of lifestyle choices.
- **Random Forest**: To capture complex relationships and interactions between features.
- **Support Vector Machine (SVM)**: For high-dimensional data classification.

### Model Training
- **Training Data**: 80% of the dataset.
- **Testing Data**: 20% of the dataset.

---

## Visualizations

### EDA Visualizations
- **Distribution of Age**: Histogram showing age distribution among individuals.
- **Spending Habits**: Box plots comparing average monthly spending across different lifestyle choices.
- **Correlation Matrix**: Heatmap illustrating correlations between features.

---

## Model Performance

- **Accuracy Score**: Classification model performance.
  
### Data Preprocessing
1. Handle missing values.
2. Visualize the target variable distribution to check for class imbalance.
3. Encode categorical features and the target variable.
4. Drop columns with high collinearity, high dimensionality, and redundancy.

---

## Tutorials

### Data Preprocessing Tutorial
1. Load the dataset using Pandas.
2. Handle missing values.
3. Visualize target variable distribution.
4. Encode categorical features.
5. Encode target.
6. Drop high-collinearity, high-dimensionality, and redundant columns.

### Model Training Tutorial
1. Split the dataset into training and testing sets.
2. Train the model using selected algorithms.
3. Evaluate the model using accuracy and confusion matrix metrics.

**Evaluation Metrics**: Measure model performance with precision, recall, and F1-score for comprehensive assessment.

---

## Report Findings

- **Model Accuracy**: Achieved 71% accuracy on the testing dataset.
- **Key Features Influencing Lifestyle Choices**:
  - Tech-Savviness Score, Investment Portfolio Value, Risk Tolerance in Investments
  - Average Weekly Exercise Hours, Environmental Awareness Rating, Financial Wellness Index
  - Social Media Influence Score, Health Consciousness Rating
  - Average Monthly Spend on Entertainment, Stress Management Score
  - Investment Risk Appetite, Number of Online Purchases, Average Daily Screen Time
  - Education Level, Lifestyle Balance Score, Time Management Skill, Work-Life Balance Indicator, Eco-Consciousness Metric
- **Conclusion**: The model effectively predicts lifestyle choices based on input features.

---

## Future Work

- Explore additional features for improved predictions.
- Perform hyperparameter tuning to improve accuracy.
- Consider model deployment.
- Implement user feedback mechanisms to enhance model performance.

---

## Data source
please find the dataset following this google drive link https://drive.google.com/file/d/1bxelbZLE55icjC6IBNGO1curpWFTVxEy/view?usp=sharing
