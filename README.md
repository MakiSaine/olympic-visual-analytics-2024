# Olympic Visual Analytics 2024

This project presents a comprehensive visual analytics case exploring the historical performance of Norwegian Olympic athletes.  
The analysis was created and implemented in **Tableau Desktop** to demonstrate how storytelling and data visualization can uncover patterns, comparisons, and insights across more than a century of Olympic history.  

The dashboard combines interactivity, narrative design, and statistical clarity to show how Norway’s athletes have evolved in participation and performance from 1896 to 2016.

---

## Table of Contents
- Overview  
- Explanatory Text  
- Design Explanation  
- Dashboard Insights  
- Recommendations  
- References  
- Files  
- Author  

---

## Overview

The visualization is implemented as a Tableau story that includes three core charts: participation trends, medal distributions, and top athlete achievements.  
Together, these reveal Norway’s evolution in the Olympics and its performance compared to other countries.

### Norwegian Athlete Participation and Medal Distribution
Above, the chart illustrates male and female athlete participation over time, alongside medal totals for Norwegian competitors.

![Norwegian athlete participation and medals](docs/screenshots/01_olympics_overview.png)

### Global Medal and Participation Comparison
This visualization compares Norway’s performance with other leading countries, highlighting historical strengths and emerging trends.

![Global Olympic overview](docs/screenshots/02_global_overview.png)

---

## Explanatory Text

Tableau was used to import and clean both datasets before combining them into a unified structure.  
Unnecessary fields were removed, and column names were standardized for clarity. For instance:  
- “City” was renamed to **Olympic City**  
- “Region” was renamed to **Country**  

Date fields were reformatted to *year-to-date*, and numerical columns such as *Age*, *Height*, and *Weight* were converted to numeric values.  
Geographic roles were assigned to *Country* and *Olympic City* to enable accurate mapping and visualization.

Below is a visual overview of the data cleaning and preparation workflow.

![Data cleaning workflow](docs/screenshots/03_data_cleaning.png)

The combined dataset enabled an interactive dashboard that explores participation, medal distribution, and athlete performance across all Olympic Games between 1896 and 2016.  
It was designed for analysts, historians, coaches, athletes, policymakers, and the general public — anyone interested in understanding Norwegian sports achievements through a data-driven lens.

---

## Design Explanation

The design focuses on clear storytelling supported by consistent use of color, annotation, and interactivity.  
The visualization types include line charts for trends, bar charts for comparisons, and bubble charts for individual achievements.

According to **Kirk (2019)**, line charts improve perceptual accuracy by representing quantitative values through proportional line size and position.  
This allows both detailed analysis and quick comprehension of temporal trends.

Bubble charts visualize individual medals, and bar charts compare results among nations — differentiated by color for gender and medal type.  
The deliberate use of **gold, silver, and bronze** aligns the story visually and semantically, enhancing clarity and engagement.

> “When it comes to explanatory analysis and leveraging visuals to share information, thoughtful use of color and text helps focus the story.”  
> — Knaflic, 2015, *Storytelling with Data*

Interactivity was integrated through hover tooltips and annotations to guide user attention toward key findings.  
These design choices make the presentation both educational and engaging.

![Dashboard design and interactivity](docs/screenshots/04_chart_design_example.png)

---

## Dashboard Insights

The final Tableau story presents several connected insights:

- **Participation growth:** Clear increase in athlete participation, particularly among women, from 1896 to 2016.  
- **Medal comparison:** Norway consistently ranks high among smaller nations, especially in winter sports.  
- **Individual excellence:** Certain athletes dominate the medal tables, demonstrating the country’s success in cultivating elite competitors.  

---

## Recommendations

The visualization results lead to several practical insights and recommendations:

- **Focus on key sports:** Continue investing in disciplines with strong historical medal yields, such as skiing, rowing, and athletics.  
- **Encourage female participation:** Build on the upward trend of female athletes competing in Olympic events.  
- **Prioritize age 20–25:** Data shows this age group consistently wins the most medals.  
- **Strengthen winter dominance:** Maintain Norway’s advantage in winter categories to secure more medals in future games.

![Recommendations summary](docs/screenshots/05_recommendations_chart.png)

---

## References

- Kirk, A. (2019). *Data Visualisation: A Handbook for Data Driven Design.* Sage Publications.  
- Knaflic, C. N. (2015). *Storytelling with Data: A Data Visualization Guide for Business Professionals.* Wiley.

---

## Files

**Interactive Dashboard**  
`Norwegian_Olympics_Dashboard.twbx` – Full Tableau dashboard with interactivity and story design.  

**Report (PDF)**  
`docs/penetration_case_extended_2024.pdf` – Analytical explanation and visual summary.  

**Screenshots**  
Located in `docs/screenshots/` folder.  

---

## Author

**Mahamed Maki Saine**  
Data Visualization & Cybersecurity Enthusiast  
📍 Norway | Tableau | Analytics | Storytelling with Data  

---

*© 2024 Mahamed Maki Saine – Created independently as part of an ongoing professional visualization portfolio.*

