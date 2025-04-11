# DP-203-Lab4
# 📊 **DP-203_Lab4 - Analyzing Data with Azure Synapse Spark Pools**

---

## ✨ **Lab Objective**

In this lab, we will focus on using **Azure Synapse Analytics Spark Pools** to perform data analysis on a lake database. You will get hands-on experience with the following tasks:
- **Creating a Lake Database**: Define the schema and structure of the lake database.
- **Creating and Managing Tables**: Learn how to define tables, load data, and perform analysis.
- **Analyzing Data**: Write SQL queries to analyze data using the power of Synapse Analytics.

By the end of this lab, you’ll be comfortable with setting up and working with lake databases in Azure Synapse, and you will know how to perform basic data analysis using SQL.

---

## ⚙️ **Requirements & Tools**

Before starting, ensure that you have the following:

- **Azure Subscription**: An active subscription with sufficient permissions to provision Azure resources.
- **Azure Synapse Analytics**: Basic understanding of Synapse Analytics and access to the Synapse workspace.
- **PowerShell**: Knowledge of PowerShell commands to provision resources.
- **Azure Data Lake**: Basic understanding of how to work with data in a lake environment.

### Tools Needed:

- **Azure Synapse Analytics Workspace**
- **PowerShell & Cloud Shell**
- **Azure Synapse Studio**: The integrated environment for managing data and resources in Azure Synapse.
- **CSV Files**: For loading sample data into tables.

---

## 🛠️ **Steps Completed**

### 🔹 1. **Setup & Source Files**

- **Provision Azure Synapse Analytics Workspace**: 
    - Created an Azure Synapse Analytics workspace linked to a Data Lake storage account. 
    - This required using a PowerShell script and an ARM template to deploy the necessary resources.

- **Modify Permissions for the Data Lake Container**: 
    - Adjusted permissions for the data lake storage container to ensure the proper access control using an Azure AD user account.

- **Create Lake Database**: 
    - Defined and created a lake database schema under **RetailDB** in Azure Synapse, making sure that the folder structure and data format (Delimited Text) were correctly set up.

- **Create and Populate Tables**:
    - Created tables (such as Customer and Product tables) by defining the schema and loading data from CSV files (e.g., customer.csv).
    - Used Synapse Studio to manage these tables and ensure the data loaded correctly.

### 🔹 2. **Data Analysis and SQL Queries**

- **Run SQL Queries**: 
    - Verified the correct loading of data by running SQL queries to analyze the Customer data, such as finding the number of customers from specific regions or performing aggregations.
    
- **Use Pre-Existing Data**:
    - If pre-existing data was available in the data lake, we created tables directly from it and analyzed the data using SQL queries within the lake database.

---

## 📚 **Resources & Inspiration**

To get more information on each step and expand your learning, refer to these resources:

- **Microsoft Learn - DP-203**: [Microsoft Learn - DP-203](https://learn.microsoft.com/en-us/certifications/exams/dp-203)
- **Azure Synapse Analytics Documentation**: [Azure Synapse Analytics Docs](https://learn.microsoft.com/en-us/azure/synapse-analytics/)
- **GitHub Repository**: MicrosoftLearning/dp-203-Data-Engineer: [GitHub Repo](https://github.com/MicrosoftLearning/dp-203-Data-Engineer)

---

## 🧠 **What I Learned**

Throughout this lab, I learned how to:

- **Set Up and Manage a Lake Database**: I understood how to create a lake database schema in Azure Synapse Analytics and manage data storage and retrieval.
- **Work with Azure Synapse Spark Pools**: Using Spark pools within Synapse Analytics to perform data transformation and analysis on the lake database.
- **Perform SQL Queries on Data**: Running SQL queries on the tables I created and loaded, giving me a deeper understanding of SQL operations in a cloud environment.
- **Load and Transform Data**: I learned how to load data from external sources into the lake database and perform necessary transformations for analysis.

---

## **Lab Steps Overview**

1. **Provision Resources**:
    - Follow the instructions to provision the Azure Synapse Analytics workspace.
    - Use a PowerShell script to deploy the necessary resources.
    - Modify the container permissions in the Data Lake to allow for proper access and management.

2. **Create the Lake Database**:
    - Define the schema and structure of your lake database.
    - Set the folder structure and configure the data format as "Delimited Text".
    - Publish the lake database under the **RetailDB** name.

3. **Create and Manage Tables**:
    - Start by defining a custom table schema (such as a Customer table).
    - Create a table for **Product** using a template and load corresponding data from CSV files (customer.csv, product.csv).

4. **Load Data into Tables**:
    - Upload the customer and product data files to the correct folders in your data lake.
    - Use Azure Synapse Studio to upload and verify the data.

5. **Run SQL Queries**:
    - Perform SQL queries to analyze the data you have loaded into the lake database.
    - For example, you can run aggregation queries to find customer demographics or product sales analysis.

6. **Use Existing Data**:
    - If pre-existing data is available, use SQL queries to directly create tables from that data and perform analysis.
  
   
## Screenshots

![1](https://github.com/user-attachments/assets/66d798b3-9118-4075-be25-5a094c321789)

![2](https://github.com/user-attachments/assets/e9b25515-6a2a-4010-86db-41d7f41b60b0)

![3](https://github.com/user-attachments/assets/b8400be6-28c0-4f64-a68a-0025d5371339)

<img width="1335" alt="4" src="https://github.com/user-attachments/assets/04eaafe6-6407-4f0c-8f54-f3c4643b035d" />

<img width="757" alt="5" src="https://github.com/user-attachments/assets/04019005-354c-40fc-8d89-dccd945e402f" />

<img width="850" alt="6" src="https://github.com/user-attachments/assets/49719134-2ff7-4305-a460-3926819e811c" />

<img width="757" alt="7" src="https://github.com/user-attachments/assets/fc45c605-1f99-4e00-827d-8a2916aca58b" />

