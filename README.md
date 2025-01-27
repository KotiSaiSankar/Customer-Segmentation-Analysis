# Customer Segmentation Analysis Using K-Means Clustering
This project aims to segment customers into distinct groups based on demographic and behavioral data, such as age, annual income, and spending score. The insights derived from this segmentation can help businesses tailor their marketing strategies to target specific customer groups effectively.


## Project Overview
Understanding customer behavior is essential for optimizing marketing strategies and improving business performance. This project applies machine learning to segment customers into clusters using K-Means clustering based on the following features:

- **Age:** The age of the customer.
- **Annual Income:** The yearly income of the customer (in $K).
- **Spending Score:** A score assigned to customers based on their purchasing behavior.


## Features
### Data Preprocessing
- Handled missing values, if any, and normalized numerical features using **StandardScaler** for better clustering performance.
### Modeling
- Applied the **K-Means Clustering** algorithm to group customers into 5 distinct clusters.
- Used the **Elbow Method** to determine the optimal number of clusters.
### Evaluation
- Visualized the clusters using scatter plots to analyze customer segments based on annual income and spending scores.
- Generated a **Power BI dashboard** for enhanced insights and presentation.


## Tools & Technologies Used
- Python
- Scikit-learn
- Pandas & NumPy
- Matplotlib & Seaborn
- Power BI
- Jupyter Notebook


## Installation
### Clone the repository:
```
git clone https://github.com/KotiSaiSankar/Customer-Segmentation.git

```

### Install the required libraries:
```
pip install -r requirements.txt

```

## Usage
To run the project and generate insights:

- Load the dataset **(Mall_Customers.csv)**.
- Run the **K-Means Clustering** notebook to preprocess the data, perform clustering, and visualize results.
- Open the **Power BI dashboard** (CustomerSegmentation.pbix) for advanced visualizations and analysis.


## Results
- The model segmented customers into 5 clusters, such as:
  - **Cluster 0:** Low-income, low spenders.
  - **Cluster 1:** High-income, high spenders.
  - **Cluster 2:** Budget-conscious buyers.
- Provided insights on spending patterns and customer demographics for personalized marketing strategies.
- Power BI dashboard highlights cluster distributions, average spending scores, and annual income trends.


## Future Work
- Include additional features like purchase frequency, product categories, and online behavior for deeper insights.
- Deploy the model using **Flask** or **Streamlit** for interactive web-based segmentation analysis.
- Automate dashboard updates with live data integration.


## Contributing
Feel free to fork this repository and submit a pull request for any enhancements, bug fixes, or new features. For discussions or suggestions, raise an issue.

