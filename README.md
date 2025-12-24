📊 Sales Data Analysis using Apache Spark on Azure

 Project Explanation

This project focuses on analyzing large-scale sales data using **Apache Spark** on **Azure Databricks**.
The objective of the project is to process sales data efficiently and generate meaningful business insights such as sales trends, regional performance, and top-selling products.

The sales dataset is stored in **Azure Blob Storage**, and **Azure Databricks** is used as the distributed computing environment to run Spark jobs.
By using PySpark, the project demonstrates how big data can be processed faster compared to traditional single-machine processing.

Project Architecture

1. Sales data is stored in **Azure Blob Storage** as a CSV file.
2. **Azure Databricks** connects securely to Blob Storage using Spark configuration.
3. **Apache Spark (PySpark)** reads the data into a DataFrame.
4. Data cleaning and transformation operations are performed.
5. Analytical queries are executed to generate insights.
6. Results are displayed and visualized using Databricks tools.

Project Workflow

1. Created an Azure Storage Account and uploaded the sales dataset.
2. Created an Azure Databricks workspace and Spark cluster.
3. Connected Databricks to Azure Blob Storage securely.
4. Loaded the sales CSV file using Spark DataFrame API.
5. Cleaned the dataset by removing null values and converting date columns.
6. Performed sales analysis including:

   * Total sales calculation
   * Region-wise sales analysis
   * Top-selling products analysis
   * Monthly sales trend analysis
7. Displayed and visualized the results.

 Key Analysis Performed

* **Total Sales**: Calculated the overall revenue generated.
* **Region-wise Sales**: Identified regions contributing the highest sales.
* **Top-selling Products**: Found products with the highest revenue.
* **Monthly Sales Trends**: Analyzed how sales change over time.

 Technologies Used

* **Apache Spark (PySpark)** – Distributed data processing
* **Azure Databricks** – Managed Spark environment
* **Azure Blob Storage** – Data storage
* **Python** – Programming language

 Learning Outcomes

* Gained hands-on experience with Apache Spark on Azure.
* Learned how to integrate Azure Blob Storage with Databricks.
* Understood distributed data processing using PySpark.
* Performed real-world data analysis on large datasets.
* Practiced publishing projects on GitHub.

 Security Note

For security reasons, **Azure credentials and access keys are not included** in this repository.
They are configured only within the Azure Databricks environment.

 THANK YOU






