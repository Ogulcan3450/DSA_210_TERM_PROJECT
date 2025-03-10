# Project: Exploring the Relationship Between Daily Calorie Output and Instagram Story Activity

## Motivation
In this project, I aim to explore whether there is a correlation between my daily calorie output and the days I post stories on Instagram. This analysis will provide insights into how social media activity might influence physical activity.

## Description of the Dataset
The dataset for this project will consist of daily records containing the following fields:
- **Date:** The specific day when data is recorded.
- **Calorie Output:** Daily calorie output data collected from my fitness tracker (e.g., Apple Health), representing both the base metabolic rate and additional calories burned through physical activity.
- **Instagram Story Activity:** A flag or indicator showing whether I posted a story on Instagram on that day.
- **Weather Data:** Information on weather conditions for that day (e.g., temperature, humidity, weather description) obtained via an API. (Optional)

## Data Sources
- **Calorie Data:** Daily calorie output data will be collected from my fitness tracker (Apple Health).
- **Instagram Story Data:** I will manually log the days I post stories on Instagram or use Instagram’s data export feature to track story posting dates.

## Data Enrichment
To enrich this dataset, I plan to include:
- **Weather Data:** I will use an API (such as OpenWeather) to gather the weather conditions on the days I post stories, to see if environmental factors influence activity levels.

## Analysis Plan
1. **Data Collection:** Over the next month, I will log my calorie output and Instagram story activity daily.
2. **Exploratory Data Analysis (EDA):** I will explore the patterns between calorie output and Instagram activity, visualizing trends and testing hypotheses.
3. **Statistical Testing:** I will apply statistical tests to determine if there's a significant difference in calorie output on days with and without Instagram story posts.

## Tools
- **Python:** Data analysis and visualization.
- **Pandas:** Data manipulation.
- **Matplotlib:** Creating graphs and visualizations.

## Timeline
- **Data Collection:** From March 10th to April 10th.
- **EDA and Hypothesis Testing:** By April 18th.
- **Machine Learning and Final Analysis:** By May 23rd.
- **Final Submission:** By May 30th.

## Expected Findings, Limitations, and Future Work
- **Expected Findings:** I anticipate that the analysis will reveal whether there is a significant correlation between Instagram story posting and daily calorie output.
- **Limitations:** As this is a personal dataset, the results may not generalize to a broader population.
- **Future Work:** Future research could expand this analysis to include data from other individuals or integrate additional variables (such as more granular environmental factors) for a comprehensive view beyond simple correlation analysis.

## Conclusion
This project provides an initial exploration into how social media activity, specifically Instagram story posting, correlates with daily physical activity as measured by calorie output. While the current focus is on these two variables enriched by weather data, further research will aim to incorporate additional contextual factors to better understand the underlying relationships. This ongoing work will help refine the analysis and potentially uncover more complex patterns in the interaction between online behavior and physical activity.
