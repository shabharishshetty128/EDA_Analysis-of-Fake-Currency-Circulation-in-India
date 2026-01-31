# Analysis_of_Fake_Currency_Circulation_in_India & Detection_of_Fake_Currency_using_Statistical_Image_Processing_and_Machine_Learning

Counterfeit currency poses a serious challenge to India’s economic stability and public trust, contributing to financial losses and supporting illegal activities. As fake notes become more sophisticated, traditional detection methods are increasingly inefficient. This project analyzes counterfeit currency trends across Indian states using official government and law-enforcement data to identify high-risk regions. It also proposes a cost-effective, automated fake note detection system using image processing and machine learning. Trained on the Banknote Authentication Dataset, the model uses key statistical features to accurately classify genuine and counterfeit notes, offering a scalable solution for banking, retail, and digital applications.

## Overview
 - [Project Objective](#projecct-objective)
 - [Research Methodology](#research-methodology)
 - [Tools and Technology Used](#tools-and-technology-used)
 - [Data Source](#data-source)

## Project Objective
    ✓ Analyze the temporal trends of counterfeit currency circulation in India over a defined time period using historical data.
    ✓ Visualize the state-wise distribution of fake currency to identify regional patterns and potential hotspots of circulation.
    ✓ Develop a Python-based automated detection system that uses image processing and statistical analysis to distinguish between genuine and counterfeit currency notes.
    ✓ Extract and evaluate key statistical image features such as kurtosis, skewness, entropy, and variance for effective classification of currency notes.
    ✓ Apply machine learning algorithms for training and testing models that accurately classify notes as genuine or counterfeit.
    ✓ Provide a user-friendly and portable tool, in the form of a web application, that enables individuals and institutions to verify the authenticity of currency notes quickly and efficiently.
 
## Research Methodology
This project follows a two-phase methodology combining data analysis and machine learning-based detection to address counterfeit currency in India.

Phase 1: Trend & Regional Analysis
Secondary data was collected from reliable sources such as the Reserve Bank of India (RBI), National Crime Records Bureau (NCRB), and government reports. The dataset included yearly seizure counts, denominations, and state-wise distribution of counterfeit notes. After data cleaning and standardization, exploratory data analysis (EDA) was performed to identify trends and regional hotspots. Visualization tools like Tableau and IBM Cognos were used to present insights through heat maps, line charts, and tree maps.

Phase 2: Automated Fake Note Detection
A low-cost detection system was developed using the Banknote Authentication Dataset. Image processing techniques were used to extract statistical features such as variance, skewness, kurtosis, and entropy. These features were used to train machine learning models with a 70:30 train-test split. The best-performing model was integrated into a Python-based application for real-time authenticity verification. Due to dataset limitations (last updated in 2012), newer currency designs are not yet supported.

## Tools and Technology Used
 - Microsoft Excel
 - IBM Cognos Analytics
 - Tableau Public
 - Python
 - Django
 - HTML
 - CSS
 - JavaScript
 
## Data Source
 - Number of Counterfeit Notes Detected from Reserve Bank of India: Annual Report [Link:](https://rbi.org.in/scripts/AnnualReportPublications.aspx?Id=1438)
 - Denomination-wise Counterfeit Notes Detected in the Banking System [Link:](https://rbi.org.in/scripts/AnnualReportPublications.aspx?Id=1438)
 - Seizure of Fake Indian Currency Note (FICN) from National Crime Record Bureau: ‘Crime in India’ publication [Link:](https://www.ncrb.gov.in/crime-in-india.html)
 - Banknote-authentication dataset from OpenML. [Link:](https://www.openml.org/data/download/1586223/php50jXam)
 - Various Real & Counterfeit currency notes images from Kaggele

## Findings and Analysis
[FICN detected by banks in last 10 years](a)
