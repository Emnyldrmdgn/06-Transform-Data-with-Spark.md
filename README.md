# 06-Transform-Data-with-Spark.md
In this exercise, you'll use a Spark notebook in Azure Synapse Analytics to transform data in files.

# Spark Data Transformation with Synapse Studio

## Overview
This document guides you through the process of transforming data using Apache Spark in Azure Synapse Studio. You will learn how to use the provided notebook `Spark Transform.ipynb` to extract, transform, and load (ETL) data.

## Prerequisites
Before you begin, ensure you have the following:

1. **Azure Synapse Workspace**: A Synapse workspace set up within your Azure portal.
2. **Storage Account for Data Pond**: A storage account configured to hold the raw data.
3. **Apache Spark Pool**: A Spark pool to process your data.

## Steps

### 1. Open Azure Synapse Studio
- Sign in to the Azure portal and navigate to the **dp203-xxxxxxx** resource group.
- Select your **Synapse workspace**.
- On the **Overview** page, click **Open Synapse Studio**. This will open Synapse Studio in a new browser tab.
- If prompted, sign in with your Azure account credentials.

### 2. Download the Spark Transform.ipynb File
- Download the `Spark Transform.ipynb` file from the following path:
  - **Allfiles/labs/06/notebooks**
- This file contains the code that will be used to transform the data. It is typically provided as a sample process for students or data engineers.

### 3. Import the Notebook into Synapse Studio
- In Synapse Studio, navigate to the **Develop** page.
- Expand the **Notebooks** tab.
- Click the **+** icon in the upper right corner and select **Import**.
- In the dialog that opens, browse and select the `Spark Transform.ipynb` file that you downloaded earlier.

### 4. Connect the Notebook to the Spark Pool
- Open the imported notebook.
- In order to run the notebook, you need to connect it to a **Spark pool**. Select the **Sparkxxxxxxx** pool from the dropdown. This pool will provide the required processing power to transform your data.

### 5. Run the Cells in the Notebook
- Browse through the notebook and run each code cell in order. Each cell will perform specific operations to transform your data.
- The cells contain both descriptions and transformation steps. They will:
  - **Extract**: Fetch the data.
  - **Transform**: Process the data (e.g., cleaning, filtering, and grouping).
  - **Load**: Output the transformed data to a target source or database.

## General ETL Process
1. **Extract**: The first step involves extracting data from your source.
2. **Transform**: The data is processed, which typically includes cleaning, filtering, and transforming the data into the desired structure.
3. **Load**: The transformed data is then loaded into a target data source, such as a database or data lake.

## Conclusion
After following these steps, you will have successfully transformed your data using Spark in Synapse Studio. This process is fundamental for data engineers and analysts working with large datasets in cloud environments.


## Screenshots

![lab62](https://github.com/user-attachments/assets/c0a91bfb-4815-4e5c-985a-0581fac8b258)
![lab63](https://github.com/user-attachments/assets/830e810f-6f5b-4130-aa97-26e004ba214c)
![lab64](https://github.com/user-attachments/assets/2aed4013-ca0d-4749-b474-71cc3b99ad44)
![lab65](https://github.com/user-attachments/assets/a9a821dc-f45d-4654-9c61-ca18e7c32e36)
![lab66](https://github.com/user-attachments/assets/982121bc-f1ee-418c-a116-99a72d0873ff)
![lab67](https://github.com/user-attachments/assets/98d19145-9540-4691-9fe1-c30d078c89d2)
![lab68](https://github.com/user-attachments/assets/6b5e51fe-e9ad-48a4-94f2-dca6ac29e531)

