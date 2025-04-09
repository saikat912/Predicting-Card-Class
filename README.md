# Banking Project

Welcome to the **Banking Project** repository! This project aims to analyze and model customer data from a bank, focusing on customer demographics, credit utilization, attrition rates, and other financial metrics. The insights derived from this analysis can help banks improve customer retention strategies and optimize their services.

---

## Features of the Project

- **Data Analysis**: Exploratory Data Analysis (EDA) using Python libraries like Pandas, Seaborn, and Matplotlib.
- **Data Visualization**: Graphical representation of trends, patterns, and outliers in customer data.
- **Machine Learning Models**: Implementation of various classification algorithms to predict customer attrition.
- **Feature Engineering**: Transformation of categorical data for model training.
- **Performance Metrics**: Evaluation of models using metrics like Mean Absolute Error and other relevant measures.

---

## Technologies Used

The project utilizes the following technologies:

| **Libraries** | **Purpose** |
|---------------|-------------|
| Pandas        | Data manipulation and analysis |
| NumPy         | Numerical computations |
| Seaborn       | Data visualization |
| Matplotlib    | Plotting graphs |
| Scikit-learn  | Machine learning models |
| XGBoost       | Gradient boosting classifier |
| CatBoost      | Gradient boosting for categorical features |
| LightGBM      | Fast gradient boosting |

---

## Dataset Overview

The dataset contains information about bank customers, including:

- **Demographics**: Age, Gender, Marital Status, Education Level
- **Financial Metrics**: Credit Limit, Average Utilization Ratio, Total Transaction Amount
- **Behavioral Metrics**: Attrition Flag, Card Category, Contacts in the last 12 months

### Sample Columns:
| Column Name            | Description                        |
|-------------------------|------------------------------------|
| `Customer_Age`         | Age of the customer               |
| `Gender`               | Gender (Male/Female)              |
| `Attrition_Flag`       | Whether the customer has left     |
| `Credit_Limit`         | Credit limit assigned             |
| `Avg_Utilization_Ratio`| Average utilization ratio         |

---

## Exploratory Data Analysis (EDA)

Key findings from EDA include:

1. **Age Distribution**: Most customers are around 45 years old; some outliers are older.
   - Example visualization: Boxplot of `Customer_Age`.

2. **Gender Analysis**:
   - Male customers have higher average credit limits compared to female customers.
   - Utilization ratios are lower for male customers.

3. **Categorical Data Insights**:
   - Attrition rates differ across marital statuses and income categories.

---

## Machine Learning Models

The following machine learning algorithms were implemented to predict customer attrition:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting (XGBoost, CatBoost, LightGBM)
- K-Nearest Neighbors (KNN)
- AdaBoost Classifier

### Performance Evaluation:
Models were assessed using metrics such as accuracy, precision, recall, and Mean Absolute Error.

---

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/banking-project.git
   cd banking-project
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook Banking-Project.ipynb
   ```

4. Follow along with the notebook for EDA and model training.

---

## Visualizations

Here are some sample visualizations included in the project:

1. **Boxplot of Customer Age**
   - Shows age distribution with outliers.
   
2. **Credit Limit by Gender**
   - Comparison of average credit limits across genders.

3. **Attrition Rates**
   - Attrition rates segmented by marital status and income category.

---

## Contributions

We welcome contributions! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`feature/your-feature-name`).
3. Submit a pull request with detailed explanations.

---

## License

This project is licensed under the MIT License.

Feel free to explore and contribute! 🚀

