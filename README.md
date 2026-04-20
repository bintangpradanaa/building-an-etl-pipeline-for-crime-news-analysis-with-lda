# Building an ETL Pipeline for Crime News Analysis with LDA

## Resources
- 📑 [Presentation Deck](https://drive.google.com/file/d/1uivw_-zkYPpSjcjj3mm9VI5lDvwL4CxB/view)

## Project Overview
Based on data from BPS, crime cases in Indonesia increased significantly from 372,965 cases in 2022 to 584,991 cases in 2023. This highlights growing concerns around public safety driven by social, economic, and legal factors. At the same time, the large volume of crime-related news published online creates semi-structured data that is difficult to analyze manually.

This project focuses on building a **data pipeline using ETL (Extract, Transform, Load)** to structure crime news data and applying **topic modeling (LDA)** to uncover patterns and trends in criminal activity.

## Objectives
- Collect crime-related news data systematically  
- Clean and structure data for analysis  
- Identify key topics and trends in crime news  

## Data Pipeline
- **Extract**: Web scraping crime news from Detik.com (Mar 25 - Sep 25, 2025)  
- **Transform**: Data cleaning and preprocessing  
- **Load**: Store processed data into PostgreSQL  

## Methods
- ETL Pipeline  
- Text Preprocessing  
- Topic Modeling (Latent Dirichlet Allocation/LDA)  

## Tools
- Python  
- PostgreSQL  

## Key Insights
- ETL successfully transforms unstructured news data into structured datasets ready for analysis.  
- Topic modeling identifies **7 main crime topics**:
  - Theft and physical violence (dominant)
  - Sexual crimes and child abuse (dominant)
  - Political crimes and human rights violations  
  - Armed violence and separatism  
  - Financial crimes and narcotics  
  - Murder and assault  
  - Legal violations and abuse of power  
