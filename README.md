# Customer Segmentation with K-Means and Recommender System

## Overview
This project focuses on segmenting customers using K-Means clustering based on their purchasing behavior and building a personalized recommender system. By analyzing transaction data such as product quantity, unit price, and purchase frequency, the project identifies distinct customer groups and tailors recommendations to their preferences, enhancing customer satisfaction and driving sales growth.

## Dataset
The dataset contains the following key features:
- **InvoiceNo:** Invoice number associated with the transaction.
- **StockCode:** Product code for the purchased item.
- **Description:** Description of the purchased item.
- **Quantity:** Number of products purchased in the transaction.
- **InvoiceDate:** Date and time of the transaction.
- **UnitPrice:** Price per unit of the product.
- **CustomerID:** Unique identifier for the customer.
- **Country:** Country where the transaction occurred.

## Key Objectives
1. Clean and preprocess the transaction data.
2. Apply K-Means clustering to segment customers based on purchasing behavior.
3. Develop a recommendation system to suggest products based on customer segments.

## Project Structure
```
.
├── README.md                 # Documentation file
├── Customer_Segmentation_with_KMeans.ipynb  # Main analysis and recommendation notebook
├── data/                     # Contains input datasets
├── results/                  # Outputs such as plots, tables, and recommendations
└── models/                   # Saved clustering models and scripts
```

## Key Features
- **Data Cleaning and Preprocessing:** Handles missing values, duplicates, and cancelled transactions.
- **K-Means Clustering:** Groups customers based on transaction frequency, spending, and product preferences.
- **Recommendation System:** Suggests products to customers based on their cluster assignments and historical behavior.

## How to Run
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/customer-segmentation.git
    ```
2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Open and execute the `Customer_Segmentation_with_KMeans.ipynb` notebook in a Jupyter environment to follow the analysis and recommendations.

## Results
- Segmentation of customers into distinct groups with shared purchasing patterns.
- Tailored product recommendations for each customer segment.
- Visualizations of key customer behaviors and clusters.

## License
This project is licensed under the MIT License.

## Contact
For questions or feedback, feel free to reach out:
- **Email:** Adam.RivardWalter@gmail.com  
- **GitHub:** [adamw80](https://github.com/adamw80)
