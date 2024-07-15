## ✨Sales Data Aggregation Yearly 

 - Description: Created a stored procedure in the Sales database that aggregates sales by year and saves the results in an external table.
   - Steps:
     1. **Provision Azure Synapse Analytics Workspace**: Set up an Azure Synapse Analytics workspace and data lake storage using a PowerShell script and ARM template.
     2. **Query Data in Files**: Use serverless SQL pool to query and preview sales data stored in CSV files.
     3. **Transform Data Using CETAS**: Use `CREATE EXTERNAL TABLE AS SELECT` (CETAS) statements to transform and save data into external tables stored in the data lake.
     ![image](https://github.com/user-attachments/assets/5539b356-6d6f-496a-9505-22e94a95a8e6)

     4. **Encapsulate Data Transformation in a Stored Procedure**: Create a stored procedure to automate the aggregation of sales data by year and save the results in an external table.
    
     ![image](https://github.com/user-attachments/assets/3ae73071-7f2f-493e-be8a-02258dc85535)

     - Once the stored procedure is executed - a parquet file containing the aggregated yearly sales data has been created.
     ![image](https://github.com/user-attachments/assets/8b44d985-0497-47dc-94d9-cde7e42038eb)

     - These files contain the aggregated product sales data. To prove this, we can select one of the files and use the New SQL script > Select TOP 100 rows menu to query it directly.
     ![image](https://github.com/user-attachments/assets/86d45218-40f7-4e0a-bd4a-abff9a22fe85)





