## ✨Sales Data Aggregation Yearly 

 - Description: Created a stored procedure in the Sales database that aggregates sales by year and saves the results in an external table.
   - Steps:
     1. **Provision Azure Synapse Analytics Workspace**: Set up an Azure Synapse Analytics workspace and data lake storage using a PowerShell script and ARM template.
     2. **Query Data in Files**: Use serverless SQL pool to query and preview sales data stored in CSV files.
     3. **Transform Data Using CETAS**: Use `CREATE EXTERNAL TABLE AS SELECT` (CETAS) statements to transform and save data into external tables stored in the data lake.
     4. **Encapsulate Data Transformation in a Stored Procedure**: Create a stored procedure to automate the aggregation of sales data by year and save the results in an external table.
