# Setup Guide

This guide explains how to set up and run the Formula 1 Data Engineering project in Azure Databricks.

## Prerequisites

- Azure Subscription
- Azure Databricks Workspace
- Azure Data Lake Storage Gen2
- Unity Catalog enabled
- GitHub account

---

## Step 1: Create Azure Resources

Create the following resources:

- Azure Databricks Workspace
- Azure Data Lake Storage Gen2
- Azure Access Connector

---

## Step 2: Configure Unity Catalog

1. Create a Metastore
2. Create a Storage Credential
3. Create an External Location
4. Grant required permissions

---

## Step 3: Upload Source Data

Upload the sample datasets provided in the `sample_data` folder to Azure Data Lake Storage.

---

## Step 4: Import the Notebooks

Import all notebooks from the `notebooks` folder into your Databricks workspace.

---

## Step 5: Execute the Pipeline

Run the notebooks in the following order:

1. Bronze Layer
2. Silver Layer
3. Gold Layer

Alternatively, execute the Databricks Workflow if configured.

---

## Expected Output

After successful execution:

- Bronze Delta Tables
- Silver Delta Tables
- Gold Analytical Tables
- Driver Standings
- Constructor Standings
