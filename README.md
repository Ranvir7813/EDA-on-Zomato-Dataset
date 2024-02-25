# EDA-on-Zomato-Dataset
This repository includes the Exploratory Data Analysis on Zomato Dataset with the help of Python Language.

This project is an analysis of wholesale customer data using the DBSCAN clustering algorithm. The dataset contains information about customers' annual spending on various product categories, such as Fresh, Milk, Grocery, Frozen, Detergents_Paper, and Delicassen.
Dataset Description

    Channel: Type of customer, either Retail (1) or Hotel/Restaurant/Café (2).
    Region: Geographic region of the customer, represented as integers.
    Fresh: Annual spending on fresh products.
    Milk: Annual spending on milk products.
    Grocery: Annual spending on grocery products.
    Frozen: Annual spending on frozen products.
    Detergents_Paper: Annual spending on detergents and paper products.
    Delicassen: Annual spending on delicatessen products.

Project Outline

    Exploratory Data Analysis (EDA): Initial analysis and visualization to understand the distribution and relationships between different features.

    Data Pre-processing: Standardizing and scaling the data for better model performance.

    Model Training: Implementing the DBSCAN clustering algorithm to identify customer segments based on their spending patterns.

    Hyperparameter Tuning: Optimizing the DBSCAN model parameters using grid search and cross-validation.

    Evaluation: Assessing the model's performance using the Silhouette Coefficient, which measures the quality of the clustering.

Results and Insights

The DBSCAN algorithm successfully identified distinct customer segments based on their spending patterns. The Silhouette Coefficient indicated a good clustering quality, suggesting that the model effectively separated different customer groups.
Repository Structure

    Wholesale customers data.csv: Contains the original dataset.
    Wholesale_Customer_Data_Analysis.ipynb: Jupyter notebook for EDA, data pre-processing, and model training.
    README.md: Main project readme file.
    requirements.txt: List of Python libraries required to run the project.

How to Use

    Clone the repository to your local machine.
    Install the required Python libraries listed in requirements.txt.
    Run the Jupyter notebooks in the notebooks/ directory to reproduce the analysis and results.

Future Directions

    Explore other clustering algorithms and compare their performance with DBSCAN.
    Investigate additional features or data sources to improve customer segmentation.
    Develop visualizations and dashboards for better data interpretation and communication.

Contributors

    Ranvir Singh: Project Lead & Data Scientist

Feel free to fork, contribute, or suggest improvements to this project.
