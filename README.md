# 🛍️ Customer Segmentation using K-Means Clustering

## 📌 Project Overview
This project applies **K-Means Clustering** to perform **customer segmentation** using purchasing behavior data.  
By analyzing **Age, Annual Income, and Spending Score**, we group customers into **meaningful clusters** that help businesses design effective marketing strategies and improve customer satisfaction.

---

## 📂 Dataset
- **File:** `customer_data.csv`
- **Columns:**
  - `Customer ID` → Unique identifier for each customer  
  - `Age` → Age of the customer  
  - `Annual Income` → Customer’s yearly income (in $)  
  - `Spending Score` → Value assigned based on purchasing behavior  

---

## 🔧 Steps Performed
1. **Data Loading & Inspection**
   - Checked shape, data types, missing values, duplicates, and summary statistics.  

2. **Data Preprocessing**
   - Selected features: Age, Annual Income, Spending Score  
   - Scaled features using **StandardScaler** to normalize magnitudes.  

3. **Clustering**
   - Used **Elbow Method (WCSS)** and **Silhouette Score** to find optimal k.  
   - Applied **K-Means Clustering** with best k.  
   - Added `Cluster` labels to dataset.  

4. **Visualization**
   - **Elbow Plot:** Determined optimal clusters  
   - **PCA Scatter Plot:** 2D visualization with centroids  
   - **t-SNE Plot:** Non-linear cluster representation  
   - **Pair Plots & Heatmaps:** Showed feature relationships and cluster profiles  

5. **Deliverables**
   - Clustered dataset with labels  
   - Segment profiles and centroids  
   - Visualizations for analysis  
   - Business recommendations  

---

## 📊 Results & Insights
- Customers segmented into **distinct clusters**:
  - High Income – High Spending  
  - High Income – Low Spending  
  - Low Income – High Spending  
  - Young vs Mature segments  

- **Business Recommendations:**
  - Premium offers for High Income–High Spending group  
  - Loyalty programs for high-spending clusters  
  - Discounts for value-seeking customers  
  - Social media engagement for younger groups  
  - Convenience & trust-focused services for mature customers  

---

## 🚀 Expected Outcomes
- Clear **visual understanding** of customer groups  
- **Actionable strategies** for targeted marketing  
- Efficient **resource allocation**  
- Enhanced **customer satisfaction and retention**

---

## 📎 Files in Repository
- `customer_data.csv` → Input dataset  
- `customer_data_clustered.csv` → Output with cluster labels  
- `customer_data_clustered_with_segments.csv` → Output with segment names  
- `cluster_segment_summary.csv` → Per-cluster stats  
- `cluster_recommendations.csv` → Business actions per cluster  
- `README_customer_segmentation.md` → Detailed project explanation  



## 🛠️ Technologies Used
- **Python**
- **Pandas**, **NumPy** (Data handling)  
- **Scikit-learn** (Clustering, Scaling, PCA, t-SNE)  
- **Matplotlib**, **Seaborn** (Visualizations)  

BY AUTHOUR---- Mali Sreeja 
This project demonstrates how clustering can uncover **hidden patterns in customer data**.  
It provides both **technical analysis** and **business recommendations**, making it valuable for **marketing strategy and decision-making**.
