
Objectives

- Understand customer purchasing and spending patterns  
- Group similar customers using machine learning  
- Develop insights for marketing personalization  
- Support business decision-making with data-driven segmentation  



 Dataset Description

The dataset contains 1000 customer entries with the following attributes:

| Feature | Description |
|--------|-------------|
| Age | Customer's age |
| Annual Income | Customer's yearly earning  |
| Spending Score | Behavior score given by the mall (1–100) |
| Cluster | Assigned cluster from K-Means (after modeling) |


 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn


  Data Visualizations

  All graphs (included in customer_segmentation_graphs.pdf):

 - Age distribution  
 - Annual income distribution  
 - Spending score distribution  
 - Cluster count visualization  

 These graphs help in understanding the customer base before applying K-Means.

 Machine Learning Model — K-Means

  Steps followed:

 1. Data Cleaning  
 2. Exploratory Data Analysis  
 3. Feature selection  
 4. Finding optimal number of clusters (Elbow Method)  
 5. Applying K-Means clustering  
 6. Visualizing cluster outputs  
 7. Interpreting business insights  

  Cluster Insights  

  Cluster 0 – High Income, High Spending**
- Premium customers  
- Target with luxury offers and loyalty programs  

  Cluster 1 – Low Income, Low Spending**
- Price-sensitive customers  
- Promote discounts and budget-friendly products  

  Cluster 2 – Young Moderate Spenders**
- Potential growth group  
- Target with trendy and engaging campaigns  

  Cluster 3 – Older Stable Customers**
- Low churn segment  
- Focus on retention and consistent engagement  

  Conclusion

  This project successfully groups customers into meaningful clusters using K-Means.  
  The segments can be used by marketing teams to:

- Improve targeting  
- Boost customer satisfaction  
- Design personalized campaigns  
- Increase ROI  

  Future Enhancements

- Add more features (Gender, Region, Purchase History)  
- Try different clustering algorithms (Hierarchical, DBSCAN)  
- Build an interactive dashboard using Power BI or Tableau  
- Deploy clustering model using Streamlit or Flask  


---

Contact

Janet James
GitHub:(https://github.com/janetjames-j/customer_segmentation_project.git)
