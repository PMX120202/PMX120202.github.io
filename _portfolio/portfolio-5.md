---
title: "Data Pipeline for Data Enrichment"
# excerpt: " <br/><img src='/images/pipeline_enrich_data.png'>"
excerpt: |
    - **Purpose:** Enhancing existing data by supplementing additional information and images to improve chatbot training data for more accurate and informative responses.  
    - **Description:**  This project enriches data by leveraging Bing Search to fetch supplementary text and images based on category-specific keywords (e.g., landmark names, operating hours, etc.). Once the relevant content is retrieved, the output is stored in a database, ensuring efficient data management and seamless integration into subsequent processes.  
    - **Technologies:**  Python, Airflow, MongoDB, Docker, ReactJS, Azure (ContainerApp)
collection: portfolio
---


<!-- ## **Description**  
In many applications, chatbot performance heavily depends on the richness and accuracy of its training data. This project aims to **expand and refine** the dataset by leveraging **Bing Search** to fetch relevant text and images based on predefined **category-specific keywords** (e.g., landmark names, operating hours, historical significance, etc.).   -->
## **Project Context**
- **Company Project**: This project is developed as part of **AIAIVN**. It focuses on building an efficient data enrichment pipeline for chatbot training using various data sources.

## **Acchitecture**
<img src='/images/pipeline_enrich_data.png'>


## **Description** 

The data enrichment process follows these key steps:  

1. **Keyword-Based Data Retrieval:**  
   - Define structured keyword queries for different categories.  
   - Use **Bing Search API** to collect relevant text and images.  

2. **Data Processing and Validation:**  
   - Extract meaningful content from search results.  
   - Filter out irrelevant or duplicate information.  
   - Validate retrieved data to ensure accuracy and reliability.  

3. **Storage and Integration:**  
   - Store the enriched data in **MongoDB** for efficient retrieval.  
   - Maintain a structured database to support various downstream applications.  

4. **Automation & Scalability:**  
   - Implement **Apache Airflow** to schedule and manage data retrieval workflows.  
   - Containerize the pipeline using **Docker** for seamless deployment.  
   - Integrate with a **ReactJS-based frontend** to facilitate data monitoring and validation.  

By automating the data enrichment process, this pipeline ensures **scalability, consistency, and efficiency** in maintaining high-quality datasets for chatbot training. The enriched data enables chatbots to deliver **more informative responses**, improving user engagement and satisfaction.  

## **Responsibilities**  

**Crawling Data**  
   - Collect data from various sources, including existing datasets and Bing Search API.  
   - Implement automated scripts to fetch text and images based on predefined keywords.  
   - Ensure efficient and scalable data retrieval mechanisms.  

**Cleaning Data**  
   - Preprocess the collected data by removing duplicates, irrelevant content, and noise.  
   - Standardize formats for consistency across different data sources.  
   - Validate extracted information to ensure accuracy and reliability.  

**Handling Data Enrichment**  
   - Integrate supplementary information into the existing dataset.   
   - Store the processed data in a well-organized **MongoDB** database.  

**Building a Basic UI**  
   - Develop a simple **ReactJS-based frontend** for data visualization and validation.  


## **Technology Stack**  
- **Python** – Core language for data processing and API integration.  
- **Bing Search API** – Source for retrieving supplementary text and images.  
- **MongoDB** – Database for storing enriched data.  
- **Airflow** – Workflow automation and task scheduling.  
- **Docker** – Containerization for deployment flexibility.  
- **ReactJS** – Frontend for verifying data.  
- **Azure (ContainerApp)**: Platform for hosting containers. 
 
## **Tool Management and Team Size**:
- **Tool Management**: Github
- **Team Size**: 3


