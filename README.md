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
- Clean the data, handle missing values, and standardize formats.

### Data Visualization
- Use scatter plots and heatmaps to explore relationships between phone usage, sleep, energy, and caffeine intake.
- Identify patterns and trends in time series data.

### Statistical Analysis
- Perform **correlation analysis** to quantify relationships between variables.
- Use **regression analysis** to evaluate the strength of indirect effects.
- Conduct **time-series analysis** to observe behavioral changes over time.

---

## Example Analysis

Some of the key analyses I plan to run:

1. **Does high phone usage affect my sleep duration?**  
   - Plot phone usage vs. sleep duration over time to check for trends.
2. **Does sleep duration impact my energy levels the next day?**  
   - Compare daily energy scores to the previous night's sleep duration.
3. **Do I drink more caffeine on low-energy days?**  
   - Track caffeine intake on days where energy levels are below 3.
4. **Can reducing screen time before bed improve sleep?**  
   - Identify days where screen time was low before bed and compare sleep duration.

---

## Conclusion & Goals

By the end of this project, I hope to answer these key questions:

- Does excessive phone usage negatively impact my sleep?  
- Can reducing screen time lead to better sleep and higher energy levels?  
- Is my caffeine intake directly linked to sleep and energy fluctuations?  
- What small, data-driven changes can I make to improve my daily routine?  

This project isn’t just about tracking numbers—it’s about using data science to improve my daily life in a measurable way. I’m excited to see what the data reveals and how I can use these insights to develop healthier habits.

---
