## Azure Services

### What are the different types of Azure Storage?
**Answer:** Azure provides Blob Storage, File Storage, Queue Storage, and Table Storage.

### What is Azure Virtual Network (VNet), and how does it work?
**Answer:** VNet allows secure communication between Azure resources and on-premises networks using VPN or ExpressRoute.

### What is Azure DevOps, and why is it used?
**Answer:** Azure DevOps provides CI/CD pipelines, version control (Git), and project management tools.

### What is Role-Based Access Control (RBAC) in Azure?
**Answer:** RBAC helps manage user permissions in Azure by assigning roles like Reader, Contributor, and Owner.

### How does Azure Monitor help in cloud applications?
**Answer:** Azure Monitor collects, analyzes, and acts on telemetry data from applications and resources.

---

## Azure Data Analytics

### What is the difference between Azure Data Lake Storage (ADLS) Gen1 and Gen2?
**Answer:** Gen2 provides hierarchical namespaces, better security, and integration with big data processing.

### Explain Azure Synapse Analytics and how it differs from Azure SQL Database.
**Answer:** Synapse Analytics is a data warehousing solution optimized for large-scale analytics, while Azure SQL is an OLTP database.

### How does Azure Databricks differ from Azure Synapse?
**Answer:** Databricks is optimized for big data and machine learning, whereas Synapse is focused on structured data and reporting.

### What is Azure Stream Analytics, and where is it used?
**Answer:** It processes real-time streaming data from IoT devices, logs, or social media feeds.

### What is Azure HDInsight, and what technologies does it support?
**Answer:** Azure HDInsight is a cloud service that provides managed clusters for Hadoop, Spark, Hive, and Kafka.

---

## Azure Data Factory (ADF)

### What is Azure Data Factory, and why is it used?
**Answer:** ADF is an ETL (Extract, Transform, Load) service that orchestrates data movement between sources.

### What is the difference between ADF Data Flow and ADF Pipeline?
**Answer:** Data Flow handles transformations visually, whereas Pipeline manages data movement and workflow execution.

### What is the role of Integration Runtime (IR) in ADF?
**Answer:** IR executes activities and facilitates data movement between on-premises and cloud sources.

### How do you handle errors in ADF pipelines?
**Answer:** Using retry policies, logging in Azure Monitor, and implementing failure activities.

### What are Linked Services, and why are they important in ADF?
**Answer:** They define connection details for external data sources like SQL, Blob Storage, and APIs.

### What are parameters and variables in ADF?
**Answer:** Parameters pass values dynamically, while variables store temporary values in pipelines.

### How does ADF support incremental data loads?
**Answer:** Using watermarking techniques like LastModifiedDate or incremental queries.

### What is the difference between Lookup and ForEach activities in ADF?
**Answer:** Lookup fetches a single value or dataset, while ForEach iterates over a collection of items.

### How can you schedule and automate ADF pipelines?
**Answer:** Using triggers such as schedule-based, event-based, or tumbling window triggers.

### How do you monitor and debug ADF pipeline failures?
**Answer:** Using ADF monitoring tools, Azure Log Analytics, and Pipeline Run history.
    
