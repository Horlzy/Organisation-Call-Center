# Organisation Call Center
Analyzing Call Center Data for Performance Optimization.

## Introduction
This project aimed to analyze call center data to identify patterns, trends, and areas for improvement to enhance overall performance and customer satisfaction. By leveraging data-driven insights, the aim was to optimize call-handling processes, reduce wait times, increase first-call resolution rates, and ultimately improve the efficiency and effectiveness of call center operations.

![Call Center Dasboard](https://github.com/Horlzy/Organisation-Call-Center/assets/74312225/63b60928-8e39-4f9a-91b3-45c97bf7125f)


## Data Sources
The primary dataset used for this analysis is the ["Excel Data Set.xlsx"](https://github.com/Horlzy/Organisation-Call-Center/blob/main/Call%20Center.xlsx) file, containing detailed information on calls in 2020.

## Tool Utilised
Excel
- Data Cleaning
- Data Analysis
- Visualization

## Data Cleaning/Preparation
In the data preparation phase, tasks included:
 - Removing duplicates.
 - Handling missing values.
 - Cleaning and formatting values.

## Exploratory Data Analysis (EDA)
EDA process of this project involved exploring the data to answer critical questions, such as:
1. Overall Response Time: Understanding the distribution of response times across all calls to assess efficiency and adherence to service level agreements (SLAs).
2. Reasons for Calls: Analyzing the primary reasons customers contact the call center to identify common issues or concerns.
3. States with the Highest Inbound: Identifying states with the highest volume of inbound calls to understand geographical demand patterns and potential regional disparities.
4. Sentiments by Call Center: Analyzing customer sentiments expressed during calls to assess overall satisfaction levels and identify any recurring issues or pain points.
5. Inbounds by Channel: Investigating the distribution of inbound calls across different communication channels (e.g., call center, chatbot, email, web) to understand channel preferences and optimize resource allocation.

## Data Analysis
Data analysis was performed in Excel, utilizing Pivot tables and formulas such as:
 - Getpivotdata()
 - IfError()

## Findings
1. Overall Response Time:
 - Response time distribution:
   24.74% below SLA.
   62.61% within SLA.
   12.65% above SLA.
2. Reasons for Calls:
 - Billing questions accounted for approximately 71% of calls.
3. Inbound Rates by State:
 - California and Texas had the highest inbound rates at 11% each.
 - Florida and New York followed at 9% and 5% respectively.
 - Other states had inbound rates that were less than 5%.
4. Sentiments Analysis:
 - Negative sentiments were prevalent, covering at least 50% at each center.
 - Positive sentiment coverage averaged at 21%.
5. Inbound Distribution by Channel:
   Call-Center: 32%
   Chatbot: 25%
   Email: 22%
   Web: 19%

## Recommendations
Based on the findings, several recommendations can be made to enhance call center performance:
- Focus on Improving Response Times: Though most responses are within SLA, efforts should be made to reduce the proportion of reactions above SLA, possibly by streamlining processes or increasing staffing during peak hours.
- Address Billing Queries: Given that billing questions are the primary reason for calls, providing more comprehensive resources for self-service or improving training for call center agents in handling billing inquiries could help reduce call volumes and enhance customer satisfaction.
- State-Specific Strategies: Since California and Texas have the highest inbound rates, tailoring strategies specific to these states might be beneficial. This could involve localized marketing efforts or specialized customer support services.
- Sentiment Analysis for Improved Customer Experience: Understanding the reasons behind negative sentiments and addressing them could significantly improve overall customer satisfaction. Regular sentiment analysis and proactive measures to address common concerns can be implemented.
- Optimize Channel Distribution: With different inbound rates across channels, optimizing resources and efforts towards the most utilized channels could lead to more efficient operations. This could involve reallocating resources or enhancing self-service options on high-traffic channels.
- By implementing these recommendations, the call center can streamline operations, improve customer satisfaction, and enhance overall performance.
