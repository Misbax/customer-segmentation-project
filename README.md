# Customer Segmentation Project

## Objective
Segment customers based on purchase behavior and demographics, visualize the resulting groups, and generate targeted business insights.

## Method
- Python / scikit-learn
- StandardScaler for feature standardization
- K-Means clustering
- Silhouette score used to compare k = 3 to 6
- Selected clusters: **3**
- Interactive HTML dashboard for segment exploration

## Features Used
- Annual_Income_INR
- Purchase_Frequency
- Average_Order_Value_INR
- Annual_Spend_INR
- Recency_Days
- Online_Purchase_Ratio
- Discount_Usage_Ratio
- Loyalty_Score

## Dashboard
The `index.html` file provides:
- Customer count
- Average annual spend
- Average purchase frequency
- Average loyalty score
- Segment distribution
- Average spend by segment
- Segment profile table
- Filters for segment, city, and preferred category
- Targeted recommendations

## Files
- `index.html` - interactive dashboard
- `data/customer_data.csv` - customer-level dataset with cluster/segment labels
- `data/segment_summary.csv` - segment-level summary
- `notebooks/customer_segmentation_analysis.ipynb` - clustering workflow
- `report/Customer_Segmentation_Project_Report.pdf` - project report

## How to Publish on GitHub Pages
1. Create a public GitHub repository.
2. Upload the contents of this project folder.
3. Go to **Settings -> Pages**.
4. Select **Deploy from a branch**.
5. Choose `main` and `/ (root)`.
6. Save.
7. Use the generated GitHub Pages URL as the assignment submission link.

## Dataset Note
The dataset is illustrative and generated for academic demonstration. It is not presented as data from a real company.

## Expected Learning Outcomes
Customer analytics, feature preparation, clustering, segmentation, visualization, and targeted business insight generation.
