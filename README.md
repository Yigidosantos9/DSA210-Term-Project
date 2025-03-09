# PhoneUsage-Caffeine-Sleep-Energy Project

## DSA210 - Data Science Term Project Overview

I am a student from Sabancı University, Furkan Yiğit Bakım, and this is my DSA210 term project. Over the next three months, I'm going to track how my daily phone usage indirectly affects my sleep duration, sleep quality, daily energy levels, and caffeine intake. I'm curious to see if spending more time on my phone negatively impacts my sleep, reduces my overall energy, and leads me to consume more caffeine to stay alert.

My plan is simple: collect daily data on phone usage, sleep duration, energy levels, and caffeine intake. Using data visualization and statistical analysis techniques, I’ll explore patterns, test hypotheses, and see if I can make meaningful improvements in my daily routine.


---


## Hypothesis
### Null Hypothesis (H₀):
- There is no significant relationship between phone usage and sleep parameters (duration and quality), energy levels, and caffeine consumption. Increased phone usage does not significantly impact sleep, energy, or caffeine intake.

### Alternative Hypothesis (H₁):
- There is a significant relationship between phone usage and sleep parameters (duration and quality), energy levels, and caffeine consumption. As phone usage increases, sleep duration decreases, sleep quality worsens, energy levels drop, and caffeine consumption increases as a compensatory response.

---

## Objectives

### Understand Indirect Effects  
- Investigate how phone usage influences sleep duration, energy levels, and caffeine intake over time.

### Identify Key Patterns  
- Determine if increased phone usage leads to shorter sleep, lower energy, and increased caffeine consumption.

### Optimize Daily Habits  
- Use data-driven insights to adjust my habits, aiming for better sleep and reduced dependence on caffeine.

### Apply Data Science Skills  
- Put into practice the concepts learned in DSA210 by conducting real-world data collection, analysis, and visualization.

---

## Motivation

This project matters to me because it directly connects to my daily habits and well-being. Here’s why I’m excited about it:

- **Personal Growth** – Understanding my own habits to improve my productivity, sleep, and energy levels.
- **Data-Driven Insights** – Moving away from assumptions and using actual data to make smarter decisions.
- **Practical Application** – Applying data science techniques to something meaningful in my life.
- **Long-Term Impact** – Learning how to optimize my phone usage for better overall health and performance.

---

## Dataset

I’ll be tracking my daily habits for three months and recording them in an Excel spreadsheet:

- **Date** – The specific day of the record.  
- **Phone Usage (min)** – Total daily phone usage, collected from iPhone’s Screen Time feature.  
- **Sleep Duration (min)** – Total sleep duration per night, recorded using the iPhone Health app.
- **Sleep Quality (1-5)** – Self-rated sleep quality, based on a scale of 1-5.  
- **Energy Level (1-5)** – Self-rated energy level, averaged from morning, afternoon, and evening assessments.  
- **Caffeine Intake (mg)** – Total daily caffeine consumption, manually recorded based on beverage type.  
- **Drinks Consumed** – A record of the specific beverages I drank (coffee, tea, energy drinks, etc.).  

I’ll ensure consistency in data logging and flag outliers (e.g., days when I’m sick or traveling).

---

## Tools & Technologies

I’ll use the following tools to collect, analyze, and visualize my data:

- **Python** – For data analysis and visualization.
- **Pandas** – To organize and preprocess data.
- **Matplotlib & Seaborn** – For scatter plots, heatmaps, and time series visualization.
- **Excel** – To manually log daily data.
- **GitHub** – For project documentation and version control.

---

## Analysis Plan

### Data Collection
- Regularly log data in Excel and import it into Python using Pandas.
- Clean the data, handle missing values, and standardize formats (e.g., converting hours to minutes).

### Data Visualization
- Use scatter plots to explore pairwise relationships (e.g., phone usage vs sleep quality, caffeine intake vs energy levels).
- Use heatmaps to visualize overall correlations between all tracked variables.
- Create time series plots to observe how variables like phone usage and sleep evolve over time.

### Hypothesis Testing
- Test hypotheses such as:
  - **H₀**: Phone usage has no significant effect on sleep, energy, or caffeine consumption.
  - **H₁**: Phone usage significantly impacts sleep (duration and quality), energy levels, and caffeine consumption.
- Conduct **correlation significance tests** and **regression analysis** to determine if observed relationships are statistically significant.
- Example: Perform a regression analysis to see if higher phone usage predicts shorter sleep duration or poorer sleep quality.

### Trend Analysis
- Investigate patterns over time, such as:
  - How phone usage and sleep patterns change during exam periods.
  - Whether there are cumulative effects (e.g., multiple nights of poor sleep increasing caffeine intake).
- Compare data from stressful periods (like exams) vs normal days to see how behaviors change under pressure.

### Example Analysis
- **Phone usage vs sleep quality**: Create a scatter plot and calculate correlation coefficient.
- **Caffeine intake on low-energy days**: Analyze whether caffeine consumption increases when energy level is below 3.
- **Time-series visualization**: Plot phone usage and sleep quality over time to see if reducing phone usage improves sleep.

---

## Findings (Expected Outcomes)

While I haven't collected enough data yet to analyze, I expect to find that:

- **Higher phone usage** will correlate with **shorter and lower-quality sleep**.
- **Poor sleep quality and duration** will lead to **lower energy levels** the next day.
- **Low energy days** will be associated with **higher caffeine intake**.
- Reducing evening phone usage may improve both sleep and energy levels.

---

## Limitations and Future Work

### Limitations:
- **External factors**, such as exam periods or unexpected life events, may influence sleep, energy, and caffeine consumption patterns, making it harder to isolate the effect of phone usage.
- Exam stress might independently affect sleep and caffeine habits, creating confounding variables that can interfere with identifying clear relationships between phone usage and other factors.
- Data is limited to **one individual**, so results may not be generalizable to others.

### Future Work:
- **Expanding dataset** by including more participants with diverse routines to enhance the generalizability of the findings.
- Longer observation period to analyze **seasonal patterns or long-term effects** to capture more variability, including holidays and non-stress periods.
- Exploring **other variables**, such as exercise, diet quality, and mental well-being, to understand more complex interactions.

---

## Conclusion & Goals

By the end of this project, I hope to answer these key questions:

- Does excessive phone usage negatively impact my sleep?  
- Can reducing screen time lead to better sleep and higher energy levels?  
- Is my caffeine intake directly linked to sleep and energy fluctuations?  
- What small, data-driven changes can I make to improve my daily routine?  

This project isn’t just about tracking numbers—it’s about using data science to improve my daily life in a measurable way. I’m excited to see what the data reveals and how I can use these insights to develop healthier habits.

---
