# YouTube-Channel-Content-Category-Analysis

# 1. Problem Definition & Project Objective
Many novice creators rely on personal experience and subjective judgement to select content niches, unaware of the competition intensity, audience scale and operational characteristics of different categories. This common issue leads to wrong positioning, blind content production, wasted time and energy, and low growth efficiency.

This project analyses how content categories differ in subscriber counts, total views, and upload volume among the top 500 most-subscribed YouTube channels as of June 2024, and provides professional, data-driven insights to help new creators choose the right category, adopt a suitable posting strategy, and avoid overly competitive fields for more sustainable channel growth.

# 2. Target User
Small content creators, new YouTube channel operators, and junior MCN teams who lack systematic data support and industry analysis to make rational content planning and operational decisions.

# 3. Data Source
- Source: Kaggle, "Top 500 Most Subscribed YouTube Channels - June 2024"
- Kaggle link: https://www.kaggle.com/datasets/ritiksharma07/top-500-most-subscribed-youtube-channels-june24
- Access date: 16 April 2026
- Main variables: category, subscribers, views, total_number_of_videos

# 4. Methods / Workflow
1. Data loading: Load the raw YouTube dataset from a local CSV file
2. Column standardization: Convert all column names to lowercase to avoid matching errors
3. Data cleaning: Remove duplicate records, drop rows with missing values, and filter invalid content categories
4. Data transformation: Convert text values with K/M/B units into numeric values for calculation
5. Feature calculation: Compute average views per video to measure content efficiency
6. Exploratory data analysis: Group data by category and calculate key performance indicators
7. Data visualization: Generate bar charts, boxplots, scatter plots, and concentration charts for multi-dimensional analysis
8. Insight generation: Summarise seven evidence-based findings for target users based on analysis results

# 5. Key Findings
1. Gaming boasts the highest average subscriber count, closely followed by Music, Kids and Movies. These niches possess strong audience appeal and huge market potential, serving as priority options for new creators.
2. Kids, Music and Gaming generate the highest total views, while the News category relies on high-frequency posting to maintain stable exposure and traffic growth.
3. Gaming achieves outstanding average views per video with relatively low upload frequency, which is highly suitable for creators with limited time who focus on high-quality, in-depth content.
4。 The correlation between upload volume and viewing performance varies significantly across categories. Therefore, creators should design differentiated release strategies instead of applying a unified operational model.
5. The Music category shows scattered subscriber distribution and obvious head monopoly effects, bringing high operational uncertainty and entry barriers for novice creators.
6. Categories with a high subscriber share held by top influencers are highly monopolised. New operators are advised to avoid such overly competitive tracks to raise their success rate.
7. Rather than blindly chasing popular trends, new creators should prioritise content categories that match their personal productivity and sustainable posting ability.

# 6. Repository Structure
- youtube.csv: Raw dataset of top 500 Most Subscribed YouTube channels
- analysis.ipynb: Jupyter Notebook with complete data analysis code
- README.md: Full project introduction and documentation
- requirements.txt: List of Python dependencies required to run the analysis

# 7. How to Run
- Python version: 3.8 or above
- Required packages: pandas, matplotlib, re
- Open notebook: Open the analysis.ipynb file in Jupyter Notebook
- Additional setup: Place the CSV dataset in the same folder as the notebook

# 8. Demo Video
[Insert 1–3 minute demo video link]

# 9. Limitations
- This dataset only covers the top 500 most-subscribed YouTube channels, so the findings may not represent smaller or newer creators.
- The data is cross-sectional and reflects only one point in time (June 2024), so it cannot show changes over time.
- The dataset includes limited variables and does not capture factors such as engagement rate, audience demographics, language, or content quality.

# 10. Next Steps
- Extend the analysis with a larger and more diverse sample of YouTube channels.
- Add time-series data to explore how category performance changes over time.
- Include more variables, such as engagement metrics, region, and language, to generate deeper insights for creators.
