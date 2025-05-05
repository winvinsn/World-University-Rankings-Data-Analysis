# **World University Rankings 2025**
## Project Overview:
This data analysis explores the **QS World University Rankings 2025**, covering approximately 1,500 universities worldwide. The dataset provides key indicators such as:
1. Rankings (2024 & 2025)
2. Location, region, size, and institutional focus
3. Academic reputation, employer reputation, faculty/student ratio
4. Citations per faculty, international faculty/student ratios
5. Sustainability scores, employment outcomes, and overall scores

The goal is to extract meaningful insights to help students, universities, policymakers, and administrators make informed decisions about higher education institutions.

## Authors:
- 👨‍💻: **Nguyen Ngo, Josh Ilko**
- 📚 **Course**: Data Science 220 - Data Management for Data Sciences
- 🏫 **Institution**: Penn State University

## Dataset Details:
📂 **Source**: [Kaggle - QS World University Rankings 2025]([url](https://www.kaggle.com/datasets/melissamonfared/qs-world-university-rankings-2025/data))
-📊 **Dimensions**: df.shape - 1,503 rows × 28 columns
- 🔍 **Key Features**:

rank_2025, rank_2024

institution_name, location, region

size, focus, status (public/private)

academic_reputation_score, employer_reputation_score

citations_per_faculty_score, sustainability_score

international_students_pct, overall_score

## Research Topics:
1. Geographic Distribution
2. Regional Performance
3. Rank Improvements
4. Sustainability Comparison
5. Academic Excellence
6. Institutional Size
7. Research Impact
8. Global Diversity

## Methodology:
1. **Problem Definition**:
  - Define important metrics for evaluation
  - Identify key questions
2. **Data Exploration**:
  - Used: Pandas (for data manipulation and analysis), matplotlib.pyplot (for statistical visualizations), numpy (for numerical operations), seaborn (for enhanced static visualizations)
  - Check for inconsistencies
3. **Data Cleaning**:
  - Standardize column names
  - Handle missing data (dropna(), fillna()
  - Convert rankings to numeric values
4. **Data Analysis**:
  - Filtering data
  - Aggregration of data (mean scores by region, year-over-year changes, etc.)
  - Rankings
5. **Visualization**:
  - Bar Chart, Box Plot, Scatter Plot
6. **Conclusion**:
  - Highlight key findings
    
## Tools & Libraries:
**Python, Pandas, Matplotlib, NumPy**

## Key Insights:
1. ✅ **Top Countries**: The U.S. and U.K. lead the top 100.
2. 📊 **Sustainability**: Public universities implement stronger sustainability practices
3. 🌍 **Global Reach**: EPFL and The University of Sydney have the highest international student ratio (100%).
