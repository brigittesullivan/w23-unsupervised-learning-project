# machine_learning_project-unsupervised-learning

By: Brigitte Sullivan</br>
Submitted on: Monday November 20, 2023</br>
Lighthouse Labs Data Science Program</br>

---


## Project Outcomes
- Unsupervised Learning: perform unsupervised learning techniques on a wholesale data dataset. The project involved: 
    1. exploratory data analysis and pre-processing, 
    2. KMeans clustering, 
    3. hierarchical clustering, 
    4. and PCA.
]
## Project Description:
I applied unsupervised learning techniques to a real-world data set and use data visualization tools to communicate the insights gained from the analysis.

The data set for this project is the "Wholesale Data" dataset containing information about various products sold by a grocery store.
The project involved the following tasks:

1. Exploratory data analysis and pre-processing: 
    * import and clean the data sets (handle missing values and outliers, duplicates), 
    * analyze and visualize the relationships between the different variables,  and perform feature engineering as needed.
2. Unsupervised learning: 
    * Perform the following on the Wholesale Data Set to identify patterns and group similar data points together: 
        * k-means clustering,
        * hierarchical clustering, and 
        * principal component analysis (PCA) . 
        * Determine the optimal number of clusters and communicate the insights gained through data visualization.
3. Summarize Results
* The ultimate goal of the project was to gain insights from the data sets and communicate these insights to stakeholders using appropriate visualizations and metrics to make informed decisions based on the business questions asked.

## Findings:

Here's a subset of some of the findings uncovered during the project: 
1. a) Chanel 2 purchases much larger volumes than Channel 1
    * Recommendation: Assuming the business strategy is to maximize profits of highest spending accounts, offer incentives discounts :
        * to cluster 0 clients for fresh, grocery and frozen products
        * to cluster 3 clients for grocery, milk, fresh
      b) Chanel 2 purchases much larger volumes than Channel 1
      c) Region 3 purchase much more than other 2 channels accross all categories
2. Several product categories have high to moderate correlation. Detergents_Paper and Grocery have an almost perfectly positive linear relationship (0.92). Grocery + Milk also have a very high correlation (0.73)
3. Optimal number of clusters varied depending on clustering appreach
4. Region 3 had the highest average sales by category ( with region 2 close behind)

*Note: complete findings are in the [Unsupervised Learning Notebook](https://github.com/brigittesullivan/w23-unsupervised-learning-project/blob/main/Unsupervised%20Learning%20-%20Project.ipynb).