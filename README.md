# Analysis_of_Fake_Currency_Circulation_in_India & Detection_of_Fake_Currency_using_Statistical_Image_Processing_and_Machine_Learning

Counterfeit currency poses a serious challenge to India’s economic stability and public trust, contributing to financial losses and supporting illegal activities. As fake notes become more sophisticated, traditional detection methods are increasingly inefficient. This project analyzes counterfeit currency trends across Indian states using official government and law-enforcement data to identify high-risk regions. It also proposes a cost-effective, automated fake note detection system using image processing and machine learning. Trained on the Banknote Authentication Dataset, the model uses key statistical features to accurately classify genuine and counterfeit notes, offering a scalable solution for banking, retail, and digital applications.

## Overview
 - [Project Objective](#projecct-objective)
 - [Research Methodology](#research-methodology)
 - [Tools and Technology Used](#tools-and-technology-used)
 - [Dataset Used](#dataset-used)
 - [Data Source](#data-source)
 - [Findings and Analysis](#findings-and-analysis)
 - [Recommendations](#recommendations)
 - [Limitations](#limitations)

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
## Dataset Used
 - <a href="https://github.com/shabharishshetty128/EDA_Analysis-of-Fake-Currency-Circulation-in-India/blob/main/FICN_Data_file.xlsx">FICN_Dataset</a>
 - <a href="https://github.com/shabharishshetty128/EDA_Analysis-of-Fake-Currency-Circulation-in-India/blob/main/banknote_authentication.txt">Banknote_authentication_Dataset</a>

## Data Source
 - Number of Counterfeit Notes Detected from Reserve Bank of India: Annual Report [Link:](https://rbi.org.in/scripts/AnnualReportPublications.aspx?Id=1438)
 - Denomination-wise Counterfeit Notes Detected in the Banking System [Link:](https://rbi.org.in/scripts/AnnualReportPublications.aspx?Id=1438)
 - Seizure of Fake Indian Currency Note (FICN) from National Crime Record Bureau: ‘Crime in India’ publication [Link:](https://www.ncrb.gov.in/crime-in-india.html)
 - Banknote-authentication dataset from OpenML. [Link:](https://www.openml.org/data/download/1586223/php50jXam)
 - Various Real & Counterfeit currency notes images from Kaggele

## Findings and Analysis
Denomination and Year-wise Insights (2015-2025)
<img width="939" height="496" alt="image" src="https://github.com/user-attachments/assets/2ef12b71-1fa4-4a58-aafc-afd73c63d569" /> 
<img width="940" height="484" alt="image" src="https://github.com/user-attachments/assets/eea4f1b4-615f-41e7-a7da-a7ba86abecb3" />

 - From FY2014–15 to FY2024–25, counterfeit currency circulation shows a major spike in FY2016–17, with over 7.6 lakh fake notes worth ₹43 crore seized, largely driven by forged ₹500 and ₹1000 notes prior to demonetization.
 - Demonetization caused a sharp short-term decline, but counterfeiters quickly adapted, shifting focus to ₹200 and ₹2000 denominations.
 - Fake ₹2000 notes increased steadily until FY2023–24, followed by a sharp drop in FY2024–25 after the withdrawal of the denomination.
 - ₹100 notes consistently remained among the most counterfeited, due to their high circulation and lower public scrutiny, while lower denominations showed minimal forgery.

Regional & State-wise Insights (2016–2022)
<img width="942" height="467" alt="image" src="https://github.com/user-attachments/assets/e0f69728-2b04-4fa3-aef5-393c554dd2eb" />

 - Gujarat recorded the highest seizure value (₹355.16 crore), significantly higher than all other states.
 - National counterfeit seizures spiked in 2022, reaching ₹3,826 crore, accounting for nearly 65% of the total seizures during the period.
 - The 2022 spike was largely driven by Gujarat, likely due to strong enforcement actions or the busting of a major counterfeit network.
 - Maharashtra, Delhi, Karnataka, and West Bengal consistently ranked among the top counterfeit-prone states.
 - Delhi reported over ₹37 crore in seizures, reflecting its importance as a high-cash, high-transaction circulation hub.
 - Counterfeit activity was concentrated in economically active and border states such as West Bengal, Punjab, and Assam, indicating possible cross-border smuggling routes.
 - Smaller states and Union Territories showed minimal seizure values, suggesting lower penetration or limited circulation.

## Recommendations
 - Enhance currency security features, especially for high-use notes like ₹100 and ₹500.
 - Increase public awareness on identifying fake notes using visible security markers.
 - Strengthen border surveillance in high-risk states such as West Bengal, Punjab, and Assam.
 - Improve inter-agency coordination between RBI, banks, and law enforcement agencies.
 - Set up specialized anti-counterfeit units in states with high FICN activity.
 - Upgrade bank detection systems with advanced scanning and sorting technologies.
 - Expand the dataset to include newer banknotes and diverse counterfeit patterns.

## Limitations
 - Analysis is based on secondary data (RBI, NCRB), which may exclude undetected or unreported counterfeit cases.
 - Variations in state-wise reporting standards may affect data consistency and comparability.
 - Lack of real-time data limits tracking of ongoing counterfeit activities.
 - Detection model is trained on pre-2012 banknotes, reducing accuracy for newer ₹500 and ₹2000 designs.
 - Use of basic machine learning models limits performance compared to advanced methods like CNNs.
 - Public datasets (OpenML, Kaggle) may not reflect the latest counterfeiting techniques.

