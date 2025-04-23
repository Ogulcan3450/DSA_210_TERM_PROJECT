# Project: Exploring the Relationship Between Daily Calorie Output and Instagram Story Activity

## 📌 Motivation
In this project, I aim to explore whether there is a correlation between my daily calorie output and the days I post stories on Instagram. This analysis will provide insights into how social media activity might influence physical activity and daily energy expenditure.

---

## 📂 Dataset Description
The dataset consists of daily records from February to March 2025, including:
- **Date:** The day the data was recorded.
- **Calorie Output:** Total daily calories burned (basal metabolism + daily activities).
- **Instagram Story Activity:** A binary indicator (1 = story posted, 0 = no story).
- **(Optional)** *Weather Data*: May be integrated later using an API.

---

## 🔗 Data Sources
- **Daily Activity Data:** Collected via Apple Health and exported daily.
- **Instagram Story Logs:** Tracked manually during the period.
- **(Planned)** Weather Data: Collected via a weather API to assess environmental effects.

---

## ✨ Data Enrichment
In future phases, the dataset may be enriched with:
- Temperature, humidity, and weather conditions per day.

---

## 📊 Exploratory Data Analysis (EDA)
EDA was performed to understand patterns and trends in the dataset.

### ✅ Visualizations:
1. **Daily Calorie Output:** A line plot showing daily fluctuations in calorie burn.
2. **Instagram Story Timeline:** A dot-strip plot indicating which days included a story post.
3. **Combined Overlay:** A calorie output plot with green dots marking story-posting days for intuitive visual comparison.

### ✅ Descriptive Statistics:
- **Maximum Calorie Output:** 3395 kcal  
- **Minimum Calorie Output:** 2436 kcal  
- **Average Calorie Output:** ~2773.81 kcal  
- **Median Calorie Output:** 2751 kcal  
- **Standard Deviation:** ~182.44 kcal  
- **Story Posting Frequency:** ~27% of days

---

## 📐 Hypothesis Testing
To assess the relationship between calorie output and story posting, I conducted a **point-biserial correlation test**.

### Hypotheses:
- **H₀ (Null):** No correlation between calorie output and story activity.  
- **H₁ (Alternative):** There is a correlation between the two.

### Results:
- **Correlation Coefficient (r):** -0.2047  
- **p-value:** 0.1200  

➡️ The result is **not statistically significant** (p > 0.05), so we fail to reject the null hypothesis. This indicates that there is **no evidence of a linear relationship** between calorie output and story activity.

---

## ✅ Progress Update (as of April 18)
- ✅ Data collected (59 days from February to March 2025)
- ✅ EDA completed with visualizations and descriptive statistics
- ✅ Hypothesis testing conducted and documented

---

## 🗓️ Project Timeline
| Task                                       | Deadline     | Status        |
|--------------------------------------------|--------------|---------------|
| Submit Proposal                            | March 10     | ✅ Completed   |
| Data Collection, EDA, & Hypothesis Testing | April 18     | ✅ Completed   |
| Apply Machine Learning & Final Analysis    | May 23       | 🔜 Upcoming    |
| Final Submission                           | May 30       | 🔜 Upcoming    |

---

## 🔮 Future Work
- Apply machine learning (e.g., logistic regression) to predict story posting.
- Integrate weather/environmental factors to investigate deeper behavioral influences.

---

## 📌 Limitations
- Dataset is personal, so findings may not be generalizable.
- Instagram story logging was done manually (automation planned for future versions).

---

## 🏁 Conclusion
This project provides an initial exploration of how Instagram activity may or may not relate to physical activity. Although no significant correlation was found, the current framework sets a foundation for further exploration — especially with enriched features or broader data collection.
