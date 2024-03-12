# Customer Segmentation using KMeans Clustering

This repository contains Python code for performing customer segmentation using KMeans clustering technique. Customer segmentation is a crucial task in marketing and business analytics, where customers are grouped into distinct segments based on their behavior, characteristics, or other factors. 

## Dataset
The dataset used in this project is `Mall_customers.csv`, which contains information about customers including their gender, age, annual income, and spending score.

## Libraries Used
- `numpy`: For numerical operations and array handling.
- `pandas`: For data manipulation and analysis.
- `seaborn`: For data visualization.
- `matplotlib`: For creating plots and visualizations.
- `scikit-learn`: For implementing the KMeans clustering algorithm and data preprocessing.

## Files
- `Customer_Segmentation.ipynb`: Jupyter Notebook containing the Python code for customer segmentation.
- `Mall_customers.csv`: Dataset file containing customer information.

## Steps
1. Data Loading and Preprocessing: The dataset is loaded into a Pandas DataFrame. Missing values and duplicates are checked and handled. Gender values are encoded as 1 for 'Male' and 0 for 'Female'.
2. Exploratory Data Analysis (EDA): Various visualizations such as heatmap, box plot, bar plot, and histograms are created to understand the data distribution and relationships between variables.
3. Data Normalization: MinMax scaling is applied to normalize the 'Annual Income' and 'Spending Score' columns.
4. KMeans Clustering: The optimal number of clusters is determined using the Elbow method. KMeans clustering is then performed on the normalized data.
5. Visualization: Scatter plot is created to visualize the clusters based on 'Annual Income' and 'Spending Score'. Centroids of the clusters are also plotted.

## Usage
1. Ensure you have Python installed along with the required libraries mentioned above.
2. Clone this repository to your local machine.
3. Open and run the `Customer_Segmentation.ipynb` notebook using Jupyter or any compatible platform.

## Results
The results of customer segmentation are visualized using scatter plots, where customers are grouped into distinct clusters based on their annual income and spending score. Centroids of the clusters are also displayed for reference.
