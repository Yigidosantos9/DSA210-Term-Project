# ScreenTime-Caffeine-Sleep-Energy Project

## DSA210 - Data Science Term Project Overview

I am a student from Sabancı University, Furkan Yiğit Bakım, and this is my DSA210 term project. Over the next three months, I'm going to track how my daily **screen time** indirectly affects my **sleep duration**, **sleep quality**, **daily energy levels**, and **caffeine intake**. 

I'm curious to see if spending more time on screens (including phone, laptop, tablet, and TV) negatively impacts my sleep, reduces my energy, and leads me to consume more caffeine to stay alert. Additionally, I will take **daily weather conditions** into account as a **contextual factor** to explain any unexpected patterns in my energy levels and screen time habits.

My plan is simple: **collect daily data** on screen time, sleep, energy, caffeine, and weather. Using **data visualization** and **statistical analysis** techniques, I’ll explore patterns, test hypotheses, and seek actionable insights to improve my daily routine.

---

## Hypothesis

### Null Hypothesis (H₀):
- There is **no significant relationship** between screen time and sleep parameters (duration and quality), energy levels, and caffeine consumption. Increased screen time does not significantly impact sleep, energy, or caffeine intake.

### Alternative Hypothesis (H₁):
- There **is a significant relationship** between screen time and sleep parameters (duration and quality), energy levels, and caffeine consumption. As screen time increases, **sleep duration decreases, sleep quality worsens, energy levels drop**, and **caffeine consumption increases** as a compensatory response.

---

## Objectives

### Understand Indirect Effects  
- Investigate how **screen time** influences **sleep duration, sleep quality, energy levels,** and **caffeine intake** over time.

### Identify Key Patterns  
- Determine if **increased screen time leads to shorter or lower-quality sleep**, lower energy, and **increased caffeine consumption**.

### Optimize Daily Habits  
- Use **data-driven insights** to adjust my habits, aiming for **better sleep, improved energy**, and **reduced dependence on caffeine**.

### Apply Data Science Skills  
- Apply **real-world data science techniques** learned in DSA210, including **data collection, analysis, and visualization**.

---

## Motivation

This project is important to me because it directly connects to my daily life and well-being. Here’s why I’m excited:

- **Personal Growth** – Understanding my habits to improve productivity, sleep, and energy.
- **Data-Driven Insights** – Making smarter decisions based on real data, not assumptions.
- **Practical Application** – Applying data science to something meaningful in my life.
- **Long-Term Impact** – Learning how to manage screen time for better overall health.

---

## Dataset

I’ll be tracking my daily habits for three months and recording them in an Excel spreadsheet:

- **Date** – The specific day of the record.  
- **Screen Time (min)** – Total daily screen time, collected from iPhone’s Screen Time feature.  
- **Sleep Duration (min)** – Total sleep duration per night, recorded using the iPhone Health app.  
- **Sleep Quality (1-5)** – Self-rated sleep quality, based on a scale of 1-5.  
- **Energy Level (1-5)** – Self-rated energy level, averaged from morning, afternoon, and evening assessments.  
- **Caffeine Intake (mg)** – Total daily caffeine consumption, manually recorded based on beverage type.  
- **Drinks Consumed** – Specific beverages (coffee, tea, energy drinks, etc.).  
- **Weather Condition** – General daily weather (Sunny, Cloudy, Rainy, etc.) for contextual understanding.  

I’ll ensure consistency in data logging and flag outliers (e.g., days when I’m sick or traveling).

---

## Tools & Technologies

- **Python** – Data analysis and visualization.  
- **Pandas** – Data organization and preprocessing.  
- **Matplotlib & Seaborn** – Visualization (scatter plots, heatmaps, time series).  
- **Excel** – Manual data logging.  
- **GitHub** – Project documentation and version control.

---

## Analysis Plan

### Data Collection
- Regularly log data in Excel and import it into Python using Pandas.
- Clean and standardize data (e.g., convert hours to minutes).

### Data Visualization
- **Scatter plots** to explore relationships (e.g., screen time vs sleep quality, caffeine intake vs energy levels).
- **Heatmaps** to visualize overall correlations between all tracked variables.
- **Time series plots** to observe changes over time (e.g., screen time and sleep trends).

### Hypothesis Testing
- Test hypotheses such as:  
  - **H₀**: Screen time has no significant effect on sleep, energy, or caffeine consumption.  
  - **H₁**: Screen time significantly impacts sleep (duration and quality), energy, and caffeine intake.  
- Conduct **correlation significance tests** and **regression analysis** to determine if observed relationships are statistically meaningful.
- Example: Regression analysis to assess if higher screen time predicts shorter sleep duration or lower sleep quality.

### Trend Analysis
- Analyze patterns over time, including:  
  - How screen time and sleep patterns change during **exam periods**.
  - Whether **cumulative effects** (e.g., consecutive poor sleep days) increase caffeine intake.
  - Compare behaviors during **stressful periods (exams)** vs regular days to see how routines shift.

### Consideration of Contextual Factors (Weather)
- Use **daily weather data** to **interpret unexpected patterns** (e.g., high screen time but high energy on a sunny day).
- Weather will **not be a primary variable** but will be used to **explain anomalies** in energy or caffeine intake.

---

## Example Analysis

- **Screen time vs sleep quality**: Scatter plot and correlation coefficient.
- **Caffeine intake on low-energy days**: Analyze if caffeine consumption increases when energy level is below 3.
- **Time-series visualization**: Plot screen time and sleep quality to examine long-term trends and effects of reduced screen time.
- **Exam periods vs normal days**: Compare averages to see how exams influence sleep, screen time, and caffeine intake.

---

## Findings (Expected Outcomes)

Although I haven't completed data collection yet, I expect to find that:

- **Higher screen time** will correlate with **shorter and lower-quality sleep**.
- Poor sleep will result in **lower energy levels** the next day.
- **Low energy days** will be associated with **higher caffeine consumption**.
- **Reducing evening screen time** may improve both sleep and energy levels.
- **Weather** may help explain days that do not follow the general trend (e.g., feeling energetic despite high screen time).

---

## Limitations and Future Work

### Limitations:
- **External factors** like exam periods or personal life events may influence sleep, energy, and caffeine intake.
- **Exam stress** might independently affect sleep and caffeine habits, potentially confounding results.
- Data is based on **one individual**, limiting generalizability.

### Future Work:
- **Expand the dataset** with more participants for broader analysis.
- **Longer observation periods** to capture more variability (e.g., holidays, non-stress periods).
- Add other factors like **exercise, diet quality, or mental health indicators** for deeper understanding of daily well-being.

---

## Conclusion & Goals

By the end of this project, I aim to answer:

- Does excessive screen time negatively affect my sleep?  
- Can reducing screen time improve sleep and energy levels?  
- Is caffeine intake linked to fluctuations in sleep and energy?  
- What small, data-driven changes can I make to improve my daily habits?  

This project isn’t just about tracking numbers—it’s about using data science to improve my life in meaningful ways. I’m excited to see what the data reveals and how I can apply these insights to build healthier routines.
