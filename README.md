# Banking-Client-Insights

### Project Overview
This project demonstrates a full data pipeline, starting from data cleaning and database management to exploratory data analysis and final visualization in a business intelligence tool.

### Technologies Used
* **Data Cleaning & Preparation:** Microsoft Excel, Python (Pandas)
* **Database:** MySQL
* **Exploratory Data Analysis (EDA):** Python (Pandas, Matplotlib, Seaborn) in a Jupyter Notebook
* **Data Visualization & Dashboarding:** Power BI, DAX

### Project Workflow
1.  **Data Collection & Cleaning:** The initial dataset was collected and cleaned in Excel to handle missing values, correct data types, and ensure data integrity.
2.  **Database Management:** The cleaned data was loaded into a MySQL database. The SQL schema is available in the `/sql` folder.
3.  **Exploratory Data Analysis (EDA):** Connected to the MySQL database using Python (`mysql-connector`). Conducted a thorough EDA to identify key trends, correlations, and patterns in customer behavior.
4.  **Dashboard Creation:** The data was imported into Power BI. Complex DAX measures were created to calculate KPIs. An interactive dashboard was built to visualize the insights from the EDA.

### Key Insights from EDA
* **Cross-selling Opportunity:** Customers with high deposits are strong targets for checking and savings accounts.
* **Risk Insights:**  High correlations among loans, deposits, and business lending suggest that over-leveraged customers might concentrate financial products in one bank.
* **Segmentation:** “Amount of Credit Cards” is not informative for customer segmentation — better to focus on balances, loans, and deposits

### Power BI Dashboard Showcase
Here are some snapshots of the final interactive dashboard.

<img width="1436" height="806" alt="Screenshot 2025-09-02 155820" src="https://github.com/user-attachments/assets/a827504b-c4b9-4322-a96a-07f6fec95132" />

<img width="1438" height="801" alt="Screenshot 2025-09-02 155903" src="https://github.com/user-attachments/assets/badef5ea-cf37-43d8-bfe0-d7d420703541" />

<img width="1439" height="804" alt="Screenshot 2025-09-02 155939" src="https://github.com/user-attachments/assets/3c827b7c-e458-41d8-bc09-eb1a832e5788" />

<img width="1438" height="808" alt="Screenshot 2025-09-02 160008" src="https://github.com/user-attachments/assets/edc6705d-89f1-4a57-96e6-48427a708333" />


