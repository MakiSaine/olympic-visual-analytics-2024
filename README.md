# Olympic Visual Analytics 2024

This project presents a comprehensive visual analytics case exploring the historical performance of Norwegian Olympic athletes.  
The analysis was designed and implemented in **Tableau Desktop** to demonstrate how effective storytelling and data visualization can uncover trends, comparisons, and insights in large datasets.  

The goal was to create a data-driven, interactive dashboard that combines storytelling with visual precision, focusing on **participation trends**, **medal distributions**, and **individual athlete achievements**.

---

## Table of Contents
1. [Static Explanatory Visualization](#static-explanatory-visualization)  
2. [Explanatory Text](#explanatory-text)  
3. [Design Explanation](#design-explanation)  
4. [Recommendations](#recommendations)  
5. [References](#references)  
6. [Files](#files)  
7. [Author](#author)

---

## Static Explanatory Visualization

The final visualization is implemented as a story in Tableau Desktop.  
Several charts were created throughout the process, including **line, bar, scatter, and map charts**, though the final version highlights the three most relevant visualizations.  
The dashboard provides a clear view of how Norway has performed relative to other countries, both in terms of participation and medal counts.

### Norwegian Athlete Participation and Medal Distribution

![Olympics Overview](docs/screenshots/01_olympics_overview.png)

### Global Participation and Medal Comparison

![Global Overview](docs/screenshots/02_global_overview.png)

These visuals track Norway’s evolution in the Olympics and show how performance compares globally.  
They reveal that Norwegian athletes have maintained consistent strength in winter disciplines, while participation from both genders has increased steadily over time.

---

## Explanatory Text

Tableau was used to import and clean both datasets before combining them.  
Unnecessary columns were removed, and fields were renamed for clarity. For example:  
- “City” → **Olympic City**  
- “Region” → **Country**  

Dates were formatted as *year-to-date*, and numerical fields such as *age*, *height*, and *weight* were converted to numeric data types.  
Geographic roles were assigned to *country* and *Olympic city* to enable mapping.

The following workflow illustrates how the data was prepared for visualization:

![Data Cleaning](docs/screenshots/03_data_cleaning.png)

The dashboard integrates both **interactive** and **static** elements, providing insight into Norwegian athlete participation and medal achievements between **1896 and 2016**.  
It is designed for sports analysts, historians, policymakers, coaches, athletes, and enthusiasts interested in Norway’s performance through Olympic history.

- The **first chart** visualizes historical participation patterns for male and female athletes.  
- The **second chart** compares medal distribution across countries.  
- The **third chart** highlights top-performing athletes and their individual medal counts.

These visualizations serve as a reference for improving performance, assessing national progress, and providing historical perspective.

---

## Design Explanation

The dashboard design focuses on clarity, storytelling, and visual consistency.  
Key visualization types include line, bar, and bubble charts to represent participation, distribution, and individual results.

### Design Principles Applied

According to **Kirk (2019)**, line charts effectively communicate quantitative trends by connecting changes over time.  
They support both broad understanding and precise reading, improving perceptual accuracy.  
The bubble chart visualizes medals per athlete, while the bar chart compares medal distributions among nations, clearly differentiated by gender color coding.  
Bubble size and color (gold, silver, bronze) simplify the identification of medal types.

![Visualization Example](docs/screenshots/04_chart_design_example.png)

The dashboard also integrates interactivity and preattentive attributes — such as color, annotation, and hover functions — to guide attention to key insights.  
Users can explore individual data points for more details, creating a learning experience rather than static observation.

> “A number of preattentive attributes are employed to draw attention to the ‘Progress to date’ trend: color, thickness of line, presence of data marker and label on the final point, and the size of the corresponding text.”  
> — Kirk, 2019, *Chapter 6, p. 153*

Following **Knaflic (2015)**, the design uses color deliberately to emphasize important information.  
By using gold, silver, and bronze consistently, the dashboard aligns color with meaning, improving comprehension and narrative flow.

> “When it comes to explanatory analysis and leveraging visuals to share information, thoughtful use of color and text helps focus the story.”  
> — Knaflic, 2015, *Chapter 4, p. 110*

---

## Recommendations

Based on the findings and visual trends:

- **Select elite athletes for key sports**: Focus on disciplines like swimming, rowing, and athletics, which have historically yielded the most medals.  
- **Promote female athlete participation**: Encourage programs that support women in Olympic-level training, as female participation continues to rise.  
- **Target athletes aged 20–25**: This group historically achieves the highest medal rates.  
- **Strengthen Norway’s winter dominance**: Continue leveraging Norway’s advantage in winter sports, which consistently provide top results.

![Insight Visualization](docs/screenshots/05_recommendations_chart.png)

---

## References

- Kirk, A. (2019). *Data Visualisation: A Handbook for Data Driven Design.* Sage Publications.  
- Knaflic, C. N. (2015). *Storytelling with Data: A Data Visualization Guide for Business Professionals.* Wiley.

---

## Files

📊 **Interactive Dashboard:**  
`Norwegian_Olympics_Dashboard.twbx` – Full Tableau dashboard with all interactive elements.

📄 **Full Report (PDF):**  
`docs/vulnerability_assessment_refined_2024.pdf` – Extended analytical explanation and report.

🖼️ **Screenshots:**  
Located in `docs/screenshots/` folder.

---

## Author

**Mahamed Maki Saine**  
Data Visualization & Cybersecurity Enthusiast  
📍 Norway | Tableau | Analytics | Storytelling with Data  

---

*© 2024 Mahamed Maki Saine – Created independently for professional development and visualization portfolio purposes.*
