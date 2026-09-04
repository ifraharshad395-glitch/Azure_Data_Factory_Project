# Azure_Data_Factory_Project

## Project Overview

This project was built to understand the fundamentals of **Azure Data Factory (ADF)** and how it can be used to orchestrate data ingestion and transformation workflows.

The project focuses on creating pipelines, working with datasets and parameters, dynamically processing multiple files, and performing data transformations using **Mapping Data Flows**.

---

## Pipeline Workflow

The project includes multiple Azure Data Factory pipelines covering different concepts such as data ingestion, parameterization, file selection, and transformations.

A key pipeline follows this workflow:

```text
Source Files
     │
     ▼
Get Metadata
     │
     ▼
ForEach
     │
     ▼
Data Flow
     │
     ▼
Transformed Data

![img alt](https://github.com/ifraharshad395-glitch/Azure_Data_Factory_Project/blob/e0b04118a1667c3e67e62606c55164dcd79c895c/resourcegroup_and_resources.png)

![img alt](https://github.com/ifraharshad395-glitch/Azure_Data_Factory_Project/blob/e0b04118a1667c3e67e62606c55164dcd79c895c/pipeline.png)

![img alt](https://github.com/ifraharshad395-glitch/Azure_Data_Factory_Project/blob/e0b04118a1667c3e67e62606c55164dcd79c895c/transformations.png)


