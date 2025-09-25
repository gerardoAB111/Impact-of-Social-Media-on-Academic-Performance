# Impact of Social Media on Academic Performance (Power BI Dashboard)

## 📊 Project Overview
This project presents a Power BI dashboard analyzing the impact of social media on academic performance among graduate, non-graduate, and high school students.

---

## 🗂 Dataset
- **Source**: Kaggle ([link](https://www.kaggle.com/datasets/adilshamim8/social-media-addiction-vs-relationships))  
- **License**: Attribution 4.0 International (CC BY 4.0)  
- **Author**: Adil Shamim  
- **Records**: 705 rows, 13 columns  
- **Key Fields**: Addicted Score, Country, Gender, Most Used Platform, Mental Health Score  

---

## 📸 Dashboard 
![Dashboard Preview](`Impact of Social Media on Academic Performance.pbix`)

---

## 📑 Data Collection
- **Survey Design**: Questions adapted from validated scales on social media addiction, such as the Bergen Social Media Addiction Scale.  
- **Recruitment**: Participants were recruited through university mailing lists and social media platforms to ensure diversity.  
- **Anonymization**: No personally identifiable information was collected; data was anonymized during collection.  

---

## ⚠️ Limitations
- **Self-Report Bias**: Responses may not be fully reliable due to social pressure and social desirability effects.  
- **Cross-Sectional Design**: A one-time survey limits the ability to establish causation.  
- **Sample Not Representative**: The study may not represent the general population, particularly individuals with limited internet access.  

---

## 🎯 Goal and Features
- **Objective**: Demonstrate, through a simple dashboard, how students and non-students are affected by social media usage.  
- **Features**:  
  - Data segmented by country, gender, and academic level.  
  - Key metrics: % of affected participants, average sleep hours, average addiction score, average mental health score, and average daily usage.  
  - Highlights countries with the highest average daily usage.  
  - Displays the top 3 most used social media platforms for the selected population.  

---

## 🛠 Tools Used
- Microsoft Power BI  
- GitHub (version control & portfolio)  

---

## 🔎 Insights (without dashboard interaction)
- **India** has the highest average daily usage, totaling 354 hours.  
- **Instagram** is the leading platform (47.34%), followed by TikTok (29.28%) and Facebook (23.38%).  
- **64%** of participants reported being affected in their academic performance.  
- The **average addiction score is concerning**, as it is close to 10, falling within the high-addiction category.  
- India, ranked first in daily usage hours, records **14.8% more than the United States**, in second place. However, the gap is much wider when compared to **Mexico in third place**, with a difference of approximately **59.5%**. This suggests that social media usage is highly concentrated in the top-ranked countries, with India and the United States showing similarly high levels.  

---

## ⚙️ Procedure
- Created a DAX measure for the `Affected_Academic_Performance` column (counting "Yes" values and dividing by total responses to obtain percentages).  
- Used slicers for user segmentation.  
- Applied smart cards to display key metrics.  

---

## 📈 Results
- Although social media consumption shows a **negative effect on academic performance**, the **average mental health score** remains positive at **6.23** (scale: 0 = poor, 10 = excellent).  
- **64% of participants** reported being affected by social media in their studies.  
- **Instagram, Facebook, and TikTok** are the preferred platforms, suggesting a need for greater time management and usage supervision.  
