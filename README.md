# Customer Segmentation via K-Means & DBSCAN

## Project Summary
Built and deployed customer segmentation models using K-Means and DBSCAN on over 200,000 customer records. Enabled targeted retention strategies that boosted customer retention by 10%.

## Problem Statement
The client lacked clear segmentation of its diverse user base, limiting personalization and marketing efficiency. A segmentation model was needed to identify behavioral patterns and group customers for tailored outreach.

## Tools & Technologies Used
- **Language**: Python (Pandas, Scikit-learn, NumPy)  
- **ML Algorithms**: K-Means, DBSCAN  
- **Data Viz**: Seaborn, Matplotlib, Power BI  
- **Infrastructure**: Jupyter, AWS S3, PostgreSQL  
- **Data**: 200,000+ records including activity, tenure, transaction frequency, and churn flags

## Modeling Approach
- Engineered features such as RFM scores, last seen date, and session count
- Applied PCA to reduce dimensionality while preserving cluster integrity
- Evaluated silhouette scores and Davies–Bouldin Index to select cluster count
- Used DBSCAN to uncover outlier clusters not detected by centroid-based methods

## Visual Output (Example)
- 6 core user segments (e.g., Dormant, Champions, Bargain Seekers, At-Risk)
- Interactive dashboards to drill down by geography, tenure, and behavior

## Results & Business Impact
- **10% improvement in retention** through customized retention campaigns  
- Enabled churn scoring refinement based on cluster assignment  
- Delivered dashboards for marketing and customer success teams to plan strategies

## Monitoring & Maintenance
- Scheduled quarterly re-segmentation based on new behavior data
- Integrated with campaign management tools for segment-driven targeting

## Challenges & Learnings
- DBSCAN helped detect outliers missed by K-Means but required tuning for scale
- Non-linear clustering behavior highlighted need for dimensionality reduction
- Model interpretation was key in gaining marketing team buy-in

## Team Collaboration
- Partnered with customer success and CRM teams for feature brainstorming
- Shared segment definitions and naming conventions for better communication

## Code Availability
Due to data sensitivity and client confidentiality, source code and datasets are not publicly available.
