# Foreign Aid & HIV/AIDS Analysis (Excel Project)

## Project Overview  
**Role Fit:** Healthcare Data Analyst | Global Health Impact | Donor Funding Evaluation  
**Tool:** Microsoft Excel (Advanced)  
**Time Frame Analyzed:** 1960–2022   
**Video Demo:** [Watch Full Walkthrough on YouTube](https://www.youtube.com/channel/UCQL3Wg_j3D5TWtn6ticnTsg)

This project evaluates how global foreign aid—especially from the **United States and its affiliates**—has influenced HIV/AIDS mortality trends. Inspired by the **current withdrawal of U.S. aid**, it quantifies deaths averted, models the consequences of funding cuts, and provides actionable insights for healthcare decision-makers.

> 💡 **Background**  
> In light of the recent suspension of U.S. foreign aid contributions, especially those supporting HIV/AIDS programs, this project simulates the magnitude of lives potentially lost if donor support continues to decline—particularly in Africa.

---
![image](https://github.com/user-attachments/assets/b3843867-c884-4f14-a98d-ff090b9f81b0)

---

## 📥 Data Sources

All raw datasets were sourced from **Kaggle**:

- `AidGiven.xlsx` – Details of donor countries and amounts disbursed (1960–2022)  
- `AidReceived.xlsx` – Country-level breakdown of foreign aid received  
- `HIVData.xlsx` – Data on HIV/AIDS-related deaths and lives saved by intervention  

These were **cleaned, transformed, and merged** in Excel to support analysis.

---

## Key Skills & Thought Process

| Skill Area                | Implementation Highlights                                                                 |
|---------------------------|--------------------------------------------------------------------------------------------|
| **Entity Classification** | Created separate sheet tagging U.S. and affiliated donors for targeted analysis            |
| **Regional Filtering**    | Built a new Excel sheet for **Africa-focused data** from global aid dataset               |
| **Death Projection**      | Estimated projected deaths under various U.S. withdrawal scenarios                        |
| **Data Merging**          | Joined aid, deaths, and donor-recipient data into a master merged dataset                 |
| **Impact Modeling**       | Calculated lives saved per $1 and $1M; projected deaths due to U.S. aid withdrawal         |
| **Navigation UX**         | Added **hyperlinked buttons + custom logos** across all sheets for seamless navigation     |
| **Formula Mastery**       | Used `SUMIF`, `SUMIFS`, `VLOOKUP`, `IF`, conditional formatting, pivot tables, and charts |
| **Insights Sheet**        | Developed a decision-maker-friendly summary in `Insights.xlsx`                            |
| **Data Storytelling**     | Designed interactive dashboard visuals with **clear narrative & drill-down capabilities**  |
| **Multimedia Reporting**  | Recorded a **YouTube demo video** explaining methodology, findings, and use cases         |

---

### Dashboard Features

- 📅 **Line Chart** – Aid received over time (1960–2022)  
- 🥧 **Pie Chart** – Breakdown of U.S. donor entities 
- 📊 **Bar Charts** – Top 5 donors and top 5 recipients  
- 📈 **Stacked Area Chart** – Deaths averted vs. deaths per country/entity  
- 📉 **Scatter Plot** – Correlation of aid vs. outcomes (R² = 0.8355)  
- 🧮 **Impact Panel** – 1,800 lives saved per $1M; 10.39B lives at risk per $5.77 trillion withdrawn  
- 🗂️ **Hyperlinked Sheet Navigation** – Custom logos and hyperlinks for ease of use  
- 📌 **Insights Sheet** – Key summaries, metrics, and recommended action points  
---

## 📂 Excel Sheets Breakdown

| Sheet Name         | Purpose                                                                 |
|--------------------|-------------------------------------------------------------------------|
| `AidReceived`      | Raw dataset (1960–2022), used for trend analysis                        |
| `AidGiven``USAffiliated`     | U.S. and agency-specific contributions (PEPFAR, CDC, USAID, etc.)       |
| `AfricaOnly`       | Filtered sheet of Africa-targeted funding                               |
| `HIVData`          | HIV-related deaths and averted death records                            |
| `MergedData`       | Joined aid + outcome dataset for modeling                               |
| `Insights`         | Summarized insights, key ratios, and stakeholder takeaways              |
| `Dashboard`        | Interactive visuals, slicers, buttons, and summary stats                |
| `Logos/Navigation` | Custom-designed icons + hyperlinks for navigating between sheets        |

---

## 🛠️ Excel Functions Used

- `SUMIF` / `SUMIFS`: Aggregated multi-criteria funding totals  
- `VLOOKUP`: Combined death data with funding records  
- `IF`: Created impact flags and conditional labels  
- Pivot Tables + Pivot Charts: Enabled dynamic aggregation by year, country, donor  
- Slicers & Timelines: Provided interactive filtering  
- Stacked Area Charts: Visualized entity-level death trends

---

## 🧠 Key Analytical Insights

- **$42.19 trillion** total foreign aid analyzed  
- **56 million** deaths averted (HIV/AIDS-specific)  
- **$5.77 trillion** contributed by U.S. and its affiliates  
- **10.39 billion lives** projected at risk if $5M withdrawn  
- **Africa** accounts for the majority of aid received and lives averted  
- **Entity-specific projections** based on historical trends

---

## 💼 Strategic Relevance for Healthcare Analyst Roles

- Connects **funding policies to public health outcomes**
- Simulates **real-world funding withdrawal impacts**
- Applies **descriptive and predictive analytics** for global health decision-making
- Uses **Excel as a powerful BI tool** with full UX customization and storytelling

---

## 👩‍💻 About the Analyst

**Lorreta Anyika**  
Founder @ **ALU Datatok** | Healthcare Data & Policy Analyst | HIV/AIDS Programs | Excel | SQL | Power BI  

📌 Trained in public health informatics and statistical storytelling  
📌 Worked with health-based organizations, including hospital and donor program datasets  
📌 Passionate about using **data to advocate for health equity and global development**

- 🔗 [LinkedIn](https://www.linkedin.com/in/uchechukwu-lorreta-anyika-7b5b4a253/)  
- 📹 [YouTube Channel – ALU Datatok](https://www.youtube.com/channel/UCQL3Wg_j3D5TWtn6ticnTsg)  
- 💬 [Join our WhatsApp Community](https://chat.whatsapp.com/LhAFCcplWbf0MYfyShJTgf)

---

## 🚀 Let’s Collaborate

This dashboard transforms complex foreign aid data into meaningful visuals and metrics.  
If you’re hiring for **data-driven roles in healthcare, public policy, or donor program evaluation** — I’d love to connect!
> *Because behind every dollar in donor aid is a life that depends on it.*
