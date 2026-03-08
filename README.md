# Data Professional Global Survey Breakdown (Power BI)

> **Executive Summary:** Analyzed 630+ global data professional responses to uncover a "Satisfaction Gap": while work-life balance is rated 5.7/10, salary satisfaction lags at 4.2/10.

## 📊 The Business Challenge
The data field is rapidly evolving, yet entry barriers remain high. This project identifies the salary benchmarks, preferred tech stacks (Python vs. R), and geographical hubs to help organizations and recruiters understand the current talent landscape.

## 🛠️ Data Engineering (The "Messy" Work)
Survey data is rarely clean. I performed the following in **Power Query**:
*   **Salary Standardization:** Converted varied string inputs into a single numerical **Average Salary** column for precise calculation.
*   **Column Splitting:** De-concatenated "Multi-select" survey answers to analyze individual programming language preferences.
*   **Data Categorization:** Grouped 30+ unique job titles into 6 core personas (Data Scientist, Engineer, Analyst, etc.).

---

## 🔍 Strategic Insights

### 1. The Python Dominance
*   **Finding:** Python is the undisputed leader in the tech stack, significantly outperforming R and JavaScript.
*   **Insight:** For career switchers, Python is no longer "optional"—it is the entry requirement.

### 2. Salary vs. Role Benchmark
*   **Finding:** **Data Scientists ($88k)** earn nearly 40% more than **Data Analysts ($54k)** on average.
*   **Insight:** The "Analyst-to-Scientist" transition represents the highest potential ROI for mid-career professionals.

### 3. The "Mixed" Entry Barrier
*   **Finding:** Only 21% of respondents found breaking into data "Easy." 
*   **Insight:** There is a significant gap between learning skills and landing roles, suggesting a need for more "Portfolio-based" hiring.

---

## 📈 Dashboard Preview
![Survey Dashboard]([INSERT YOUR LINK HERE])

## 🚀 Key Recommendations
*   **For Recruiters:** Focus on "Work-Life Balance" in job descriptions to attract talent, as it is valued more than current salary levels.
*   **For Educators:** Shift curriculum focus away from Java/C++ toward Python-centric data manipulation to match market demand.
*   **For Candidates:** Target the US/UK markets for highest remote-pay potential, but look toward India for the fastest-growing talent hubs.
