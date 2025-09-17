# 🛍️ Customer Segmentation with RFM Analysis

This project demonstrates how to perform **customer segmentation** using the **RFM (Recency, Frequency, Monetary)** model on the **Online Retail dataset**.  
It groups customers based on their purchasing behavior and visualizes the results.

## 📂 Dataset

We used the **Online Retail dataset** (UCI Machine Learning Repository / Kaggle).  
You can download it from:

- [UCI Repository](https://archive.ics.uci.edu/ml/datasets/online+retail)
- [Kaggle Version (CSV)](https://www.kaggle.com/datasets/vijayuv/onlineretail)

Make sure the dataset file (`OnlineRetail.csv` or `OnlineRetail.xlsx`) is in the same folder as the notebook/script.

## 🛠️ Tools & Libraries

- Python 3.x  
- [Pandas](https://pandas.pydata.org/)  
- [NumPy](https://numpy.org/)  
- [Matplotlib](https://matplotlib.org/)  
- [Seaborn](https://seaborn.pydata.org/)  


🚀 **How to Run**

Clone this repository:

```bash
git clone https://github.com/yourusername/your-repo.git
cd your-repo
```

Upload the dataset file (`OnlineRetail.csv`) into the same directory.

Open the Jupyter Notebook or run the Python script:

```bash
jupyter notebook RFM_Analysis.ipynb
```

Or upload the notebook and dataset to Google Colab, then run all cells.

📊 **Steps Performed**

- **Data Loading & Cleaning**
  - Load dataset
  - Filter out null Customer IDs and negative quantities
  - Compute total revenue per transaction  

- **RFM Metrics**
  - Recency: Days since last purchase
  - Frequency: Number of purchases
  - Monetary: Total amount spent  

- **Scoring**
  - Each metric scored from 1–5
  - Combined into an RFM_Segment and RFM_Score  

- **Segmentation**
  - Champions  
  - Loyal Customers  
  - Potential  
  - At Risk  

- **Visualization**
  - Bar chart of customer segments  
  - Heatmap of average Monetary by Recency & Frequency scores  

📝 **Output Examples**

- Segment Table: Average Recency, Frequency, Monetary per segment with customer counts.
- Charts:
  - Distribution of customers across segments.
  - Heatmap of monetary value by R and F scores.

💡 **Marketing Strategies Ideas**

- Champions: Exclusive offers, loyalty rewards.
- Loyal Customers: Upselling or premium memberships.
- Potential: Targeted promotions to increase purchase frequency.
- At Risk: Re-engagement campaigns or discounts.

