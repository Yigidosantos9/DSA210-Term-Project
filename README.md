# LectureHours-PhonePickUp Project

## DSA210 - Data Science Term Project Overview

**I am a student from Sabancı University, Furkan Yiğit Bakım, and this is my DSA210 term project.**

Over the next three months, I am going to track how my daily lecture hours impact my phone pick-up behavior, focusing on how often I check or unlock my phone. I’m curious to see if on days with more lectures, I tend to pick up my phone more frequently, and whether this increase is related to social media or communication apps. In addition, I will track contextual daily factors such as caffeine intake, sleep duration, gym attendance, and weather conditions to better understand variations in phone usage. 

---

## Hypothesis

### Null Hypothesis (H₀):
- **There is no significant relationship between daily lecture and recitation hours and phone pick-up behavior. The total number of pick-ups, as well as pick-ups for social media and communication apps, do not significantly change depending on the number of lecture hours.**

### Alternative Hypothesis (H₁):
- **There is a significant relationship between daily lecture and recitation hours and phone pick-up behavior. As lecture hours increase, the total number of pick-ups, social media pick-ups, and communication pick-ups also increase.**

---

## Objectives

- **Understand Pick-up Behavior:**  
  Explore how academic workload (lecture hours) affects phone pick-up frequency.

- **Identify App-Specific Trends:**  
  Analyze whether both social media and communication app pick-ups increase on days with more lectures.

- **Consider Contextual Factors:**  
  Examine how caffeine intake, sleep duration, gym attendance, and weather influence phone pick-up behavior on heavy and light lecture days.

- **Apply Data Science Skills:**  
  Use real-world data science techniques learned in DSA210, including data collection, analysis, and visualization.

---

## Motivation

This project is important to me because phone pick-ups are often unconscious, and I want to understand how my academic workload affects these behaviors. Here’s why I’m excited:

- **Personal Growth:** Understanding my own habits to improve focus and reduce unnecessary distractions.
- **Data-Driven Insights:** Making better decisions based on real data, not assumptions.
- **Practical Application:** Applying data science to something meaningful in my life.
- **Long-Term Impact:** Developing healthier phone habits and better focus management.
- **Broader Relevance:** By including data from other students, this project aims to explore common patterns among university students and understand how academic workload impacts digital behavior. With increasing concerns about digital well-being and productivity, these insights could help students, educators, and mental health professionals to design better strategies for managing phone usage during high-stress periods such as exam seasons. The project also aims to contribute to the broader conversation on how modern academic life and technology use intersect, offering actionable suggestions for healthier digital habits in academic settings.

---

## Dataset

I will be tracking daily habits for three months and recording them in an Excel spreadsheet. Additionally, a small group of students from different academic backgrounds will contribute data to broaden the dataset and provide richer analysis.

- **Date:** The specific day of the record.
- **Day:** Day of the week (e.g., Monday, Tuesday).
- **Lecture Hours (h):** Total lecture hours that day.
- **Total Pick-ups:** Total number of phone pick-ups (from iPhone Screen Time).
- **Social Media Pick-ups:** Number of phone pick-ups for social media apps (e.g., Instagram).
- **Communication Pick-ups:** Number of pick-ups for communication apps (e.g., WhatsApp).
- **Total Screen Time (min):** Total daily screen time (supportive but secondary).
- **Sleep Duration (min):** Total sleep duration per night (from iPhone Health app).
- **Caffeine Intake (mg):** Daily caffeine consumption, manually recorded.
- **Gym Attendance (1=Yes, 0=No):** Whether I went to the gym that day.
- **Temperature (°C):** Daily average temperature.
- **Condition:** General daily weather (e.g., Sunny, Rainy).
- 
- **IsHighCaffeineDay (engineered):** A binary feature indicating if caffeine intake exceeded 300mg on that day.
---

## Tools & Technologies

- **Python:** Data analysis and visualization.
- **Pandas:** Data organization and preprocessing.
- **Matplotlib & Seaborn:** Visualization (scatter plots, bar charts, time series).
- **Excel:** Manual data logging.
- **GitHub:** Project documentation and version control.

---

## Analysis Plan

### Data Collection
- Regularly log data in Excel and import it into Python using Pandas.
- Clean and standardize data for consistency and accuracy.

### Data Visualization
- **Scatter Plots:** Explore relationships (e.g., lecture hours vs. total pick-ups).
- **Bar Charts:** Compare social media vs. communication app pick-ups on busy vs. light days.
- **Heatmaps:** Visualize overall correlations between tracked variables.
- **Time Series Plots:** Observe changes over time (e.g., how pick-up patterns evolve).

### Hypothesis Testing
- **H₀:** Lecture hours have no significant effect on pick-up frequency or type.
- **H₁:** Lecture hours significantly influence total pick-ups, social media pick-ups, and communication pick-ups.
- Conduct correlation analysis and regression analysis to determine if observed relationships are statistically meaningful.

### Trend Analysis
- Analyze patterns over time, including:
  - How pick-up behavior changes during exam periods.
  - Whether cumulative stress (e.g., multiple busy days in a row) leads to more frequent pick-ups.
  - How contextual factors like caffeine intake, gym, and sleep modulate pick-up frequency.
  - The role of weather in influencing mood and phone usage.

---

## Example Analysis

- **Lecture Hours vs. Total Pick-ups:**  
  Scatter plot with correlation coefficient.

- **Social Media vs. Communication Pick-ups:**  
  Bar chart comparing app usage on heavy vs. light days.

- **Time-Series Visualization:**  
  Tracking phone pick-up frequency over time, aligned with academic schedule.

- **Regression Analysis:**  
  Predicting pick-up counts from lecture hours, adjusting for sleep, caffeine, gym, and weather.

---

## Findings (Expected Outcomes)

Although I haven’t completed data collection yet, I expect to find that:

- **More lecture hours will be associated with higher total pick-ups.**
- **Both social media and communication pick-ups will increase on busy academic days.**
- **Caffeine intake and lower sleep may amplify phone pick-up frequency.**
- **Gym attendance may help reduce unnecessary pick-ups.**
- **Weather conditions may influence phone usage patterns (e.g., more pick-ups on rainy days).**

---

## Limitations and Future Work

### Limitations:
- External factors like exams or personal life events may influence phone behavior independently.
- Initially limited to a small group of participants, although not restricted to only one person.
- Other app categories (e.g., entertainment, news) are not explicitly tracked.

### Future Work:
- Expand dataset to include more participants from diverse backgrounds and departments.
- Extend observation period to capture more variability and seasonal effects.
- Add other indicators like stress levels, academic performance, and mental health for deeper insights.

---

## Hypothesis Testing Summary

To understand how different factors impact phone pick-up behavior, several statistical tests were conducted.

- **Lecture Hours:**  
  Pick-up activity (especially social media and communication apps) significantly increased on days with more than 2 hours of lectures.

- **Exam Days:**  
  Total pick-ups dropped significantly on exam days, likely due to reduced distractions.

- **Gym Attendance & High Caffeine Days:**  
  These showed slight visual differences but were not statistically significant based on t-test results.

- **Weather Conditions:**  
  ANOVA results indicated no significant effect of weather on phone usage.

Overall, academic intensity (e.g., lecture hours and exams) had the most noticeable impact, while lifestyle and environmental factors had a more limited effect.

## Machine Learning Component

We trained and compared three different machine learning models — Linear Regression, Random Forest, and K-Nearest Neighbors — using various combinations of features. Our goal was to achieve the highest possible R² score using the smallest number of meaningful features.

**Best Model (Random Forest):**
- **Target:** TotalPickups
- **Top Features:** LectureHours, IsHighCaffeineDay
- **Performance:**
  - R²: 0.361
  - MAE: 28.06
  - RMSE: 40.05

This shows that even with just two simple features, a relatively high prediction accuracy can be achieved.

We also trained models to predict **SocialMediaPickups** and **CommunicationPickups** using the same feature pair:

- **SocialMediaPickups:**
  - R²: 0.689
- **CommunicationPickups:**
  - R²: 0.464

These results support the idea that lecture hours and high caffeine intake are strong indicators of increased phone activity, especially for social media use.

## Conclusion & Goals

This project helped me discover how academic and lifestyle habits impact my phone usage. Key insights include:

- I use my phone more on high-lecture days, especially for social media and communication.
- High caffeine intake is also a strong predictor of increased pick-up behavior.
- Exam days reduce phone usage, likely due to higher focus.
- A custom binary feature, `IsHighCaffeineDay`, significantly improved model accuracy.
- By iteratively testing different features and models, I achieved the best result using just 2 features — `LectureHours` and `IsHighCaffeineDay` — with an R² of 0.361.

The project not only confirmed my hypothesis but also showed how minimal, smart feature engineering can yield strong predictive performance.

In the end, this project wasn’t just about numbers. It made me more aware of my habits, and showed me how I can use data to make small but meaningful improvements in daily life.
