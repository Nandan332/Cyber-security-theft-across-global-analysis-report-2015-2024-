# Cybersecurity Theft Analysis Report (2015-2024)

#Project Goal:

* To analyze trends and patterns in cybersecurity theft data from 2015 to 2024, focusing on financial impact, affected users, and incident resolution time, with a specific emphasis on India and global comparisons.


#Tools Used:

1. Power BI: Used for data visualization and building the dashboard.
2. Data Transformation: Data was cleaned and transformed using Power Query to prepare it for visualization in Power BI.
3. Data Model:
The data model consists of several tables, including cyberattacks, malware types, targeted industries. These tables were joined to create relationships that allowed for dynamic filtering and drill-downs in the Power BI report.
4. Visualizations:
   
    **KPI Cards: Display Number of affected users, Sum of financial losses, Average resolution time, Target industry.

    **Bar Charts: Compare Sum of Financial Loss with respective countries and Industries types.

    **Line Graphs: Show Average resolution time by Defence mechanism used.

    **Donut chart: Show Attack type and Financial Loss.

*Date of Analysis:* May 17, 2025

## 1. Executive Summary

This report presents an analysis of cybersecurity theft data spanning the years 2015 to 2024. Key findings reveal significant financial losses and a large number of affected users globally, with India being a notable case study. The analysis highlights the prevalence of specific attack types and security vulnerabilities, as well as variations in incident resolution times based on the defense mechanisms employed. Understanding these trends is crucial for organizations to implement effective cybersecurity strategies and mitigate potential risks.

## 2. Key Findings

## 2.1 India-Specific Analysis (2015-2024)

* Affected Users: Approximately *17 million* users in India were impacted by cybersecurity incidents.
* Financial Loss: Total financial losses in India amounted to $1.59 billion USD.
* Incident Resolution:* The average time to resolve a cybersecurity incident in India was 37.91 hours.

## 2.2 Financial Loss by Attack Type (Global)

* Dominant Attack Types: DDoS (18.24%), Phishing (17.62%), and Ransomware (16.61%) collectively caused the majority of financial losses.
* Highest Loss: DDoS attacks resulted in the largest financial impact ($27.63K Million).

## 2.3 Incident Resolution Time by Defense Mechanism (Global)

* Longest Resolution: Incidents where VPN was used as a defense mechanism had the highest average resolution time (~36.9 hours).
* Shortest Resolution: Incidents involving Firewall defense had the lowest average resolution time (~35.7 hours).

## 2.4 Global Financial Loss by Country

* Top Countries (by Loss): The UK experienced the highest financial loss, followed by Germany and Brazil. India's financial loss, while significant, was lower than these top countries in the analyzed dataset.

## 2.5 Affected Users by Security Vulnerability Type (Global)

* Leading Vulnerabilities: Weak Passwords (26.17%) and Unpatched Software (24.9%) were the most common vulnerabilities leading to affected users.

## 2.6 Financial Loss by Target Industry (Global)

* Most Affected Industries: The IT industry reported the highest financial losses, followed by Banking and Government sectors.


## 3. Visualizations

## 3.1. India Cybersecurity Metrics (2015-2024)

![attachment_1]( https://github.com/Nandan332/pictures/blob/main/Screenshot%202025-05-17%20193655.png)
This visual provides an overview of affected users, financial loss, and incident resolution time for India.

## 3.2. Financial Loss by Attack Type and Incident Resolution by Defense Mechanism

![attachment_2]( https://github.com/Nandan332/pictures/blob/main/Screenshot%202025-05-17%20194919.png)
The donut chart shows the distribution of financial losses by attack type, while the line chart illustrates the average incident resolution time for different defense mechanisms.

## 3.3 Global Financial Loss, Vulnerabilities, and Target Industries

![attachment_3](https://github.com/Nandan332/pictures/blob/main/Screenshot%202025-05-17%20194935.png )
This visual compares financial losses across countries, highlights the most common security vulnerabilities leading to affected users, and shows financial losses by target industry.

## 4. Discussion and Insights

The analysis reveals critical insights into the landscape of cybersecurity theft. The dominance of DDoS, Phishing, and Ransomware in causing financial damage underscores the need for robust defenses against these attack vectors. The correlation between the use of specific defense mechanisms (like Firewalls) and faster incident resolution times suggests the effectiveness of these tools in mitigating the impact of attacks.

The prevalence of weak passwords and unpatched software as vulnerabilities highlights the importance of basic security hygiene practices and regular software updates. The significant financial impact on the IT and Banking industries indicates that these sectors are prime targets and require stringent security measures.

The comparison of India's cybersecurity metrics with global data provides a valuable context for understanding the country's position in the global threat landscape.

## 5. Limitations

* The data may not represent the entire global cybersecurity landscape.
* The categorization of attack types and defense mechanisms might vary across different reporting sources.
* The analysis is based on aggregated data and does not delve into specific incident details.

## 6. Recommendations for Future Work

* Conduct a more detailed time-series analysis to identify evolving trends in attack types and financial losses.
* Explore the correlation between investment in cybersecurity measures and the reduction in financial losses or incident resolution times.
* Perform a deeper comparative analysis of cybersecurity trends across different countries and regions.
* Investigate the impact of specific cybersecurity policies and regulations on the observed trends.

## 7. Conclusion

This report provides a comprehensive overview of the cybersecurity theft data analyzed. The findings emphasize the significant financial and operational impact of cyber threats and highlight key areas that require attention for effective risk management and mitigation. Further in-depth analysis can provide even more granular insights to inform strategic decision-making in the cybersecurity domain.

The data for this project you can get it on Kaggle.com
