# Project: Exploring the Relationship Between Daily Calorie Output and Instagram Story Activity

## 📌 Motivation
In this project, I aim to explore whether there is a correlation between my daily calorie output and the days I post stories on Instagram. This analysis provides insights into how social media activity might influence physical activity and daily energy expenditure.

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
- Added temporal features such as:
  - **Day of the Week** (0 = Monday, … 6 = Sunday)
  - **Weekend Indicator** (1 = weekend, 0 = weekday)

These features enrich the dataset to better capture behavioral patterns related to posting stories.

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

➡️ The result is **not statistically significant** (p > 0.05), so we fail to reject the null hypothesis. This indicates **no evidence of a linear relationship** between calorie output and story activity.

---

## 🤖 Machine Learning Analysis

To further explore predictive relationships, I applied supervised classification algorithms to predict Instagram story posting based on calorie output and temporal features.

### Features Used:
- **Calorie Output**
- **Day of the Week**
- **Weekend Indicator**

### Models and Results:

#### Decision Tree Classifier
- Accuracy and performance metrics including cross-validation accuracy.
- Confusion matrix and classification report provide insights into model performance.
- Visualization of the decision tree shows how features influence predictions.

#### Random Forest Classifier
- Typically higher accuracy than the decision tree due to ensemble learning.
- Cross-validation scores demonstrate model robustness.
- Confusion matrix and classification report highlight precision, recall, and F1-score.

Both models show moderate predictive capability, suggesting some relationship between the features and Instagram story posting behavior, though predictions are not highly accurate.

---

## ✅ Progress Update (as of June 1)
- ✅ Data collected (59 days from February to March 2025)
- ✅ EDA completed with visualizations and descriptive statistics
- ✅ Hypothesis testing conducted and documented
- ✅ Machine learning classifiers (Decision Tree, Random Forest) implemented and evaluated

---

## 🗓️ Project Timeline
| Task                                       | Deadline     | Status        |
|--------------------------------------------|--------------|---------------|
| Submit Proposal                            | March 10     | ✅ Completed   |
| Data Collection, EDA, & Hypothesis Testing | April 18     | ✅ Completed   |
| Apply Machine Learning & Final Analysis    | May 23       | ✅ Completed   |
| Final Submission                           | May 30       | ✅ Completed   |

---

## 🔮 Future Work
- Enhance machine learning models with additional features, such as weather and social factors.
- Explore other classification algorithms and parameter tuning for improved prediction.
- Automate Instagram story logging to improve data reliability.
- Investigate time series models to capture temporal dependencies.

---

## 📌 Limitations
- Dataset is personal; findings may not generalize to broader populations.
- Instagram story logging was manual and may contain inaccuracies.
- Current models are trained on limited features and a relatively small sample size.

---

## 🏁 Conclusion
After thorough exploratory data analysis, hypothesis testing, and machine learning classification, the project finds **no statistically significant linear correlation** between daily calorie output and Instagram story activity. However, machine learning models suggest that calorie output combined with temporal features (day of the week, weekend indicator) has **some moderate predictive power** for Instagram story posting behavior, though accuracy is limited.

Overall, this indicates that Instagram story activity is not strongly determined by daily calorie expenditure alone. The relationship is likely influenced by additional factors not captured in the current dataset. This project provides a foundational framework and highlights the need for richer data and more complex models to better understand the behavioral interplay between physical activity and social media use.

---

