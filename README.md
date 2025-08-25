## Repository name
Your repostiory should be named something like `async-final-project-color-name`
Example: `async-final-project-teal-Anas`

## Dataset
[California Social Determinants of Health (SDOH):
Merging health, social & environmental metrics across CA ZIP codes for community] (https://www.kaggle.com/datasets/evanmoh/california-social-determinants-of-health-sdoh?resource=download)

## Why did I chose this dataset?

I chose the California Social Determinants of Health (SDOH) dataset because California’s unique socioeconomic landscape---from newly wealthy tech billionaires to working-class families---offers an interesting case study in healthcare equity. While these groups live different realities, both share the universal need for quality healthcare that addresses their specific needs. The dataset captures critical factors such as demographics, uninsured populations, healthcare provider access, and environmental influences like air quality, all of which can shape health outcomes. This set of variables allows for a nuanced analysis of how social determinants can impact healthcare access and utilization across California’s diverse communities, highlighting disparities and guiding data-driven policy solutions.

## Progress
- [ YES ] Picked dataset
- [ YES ] Defined 10 questions
- [ YES ] Answered 10 questions using Pandas
- [ YES ] Added at least one data visualization (using Matplotlib and/or Seaborn) to each single question
- [ NA ] Prepared presentation slides to present at graduation

## Questions
- [+] Question 1: Which ZIP code(s) have the largest population of people who speak English not well?
  - Answer: ZIP code 90011 has the largest population of residents who speak English “not well,” with approximately 19,500 people. Other ZIP codes with large limited-English populations include 90202 and 90201 (both around 17,000 people). Most of the top ZIP codes are concentrated in Los Angeles County.
  - Visualization: ![Q1 Visualization]
  
- [+] Question 2: Which ZIP code(s) has the highest percentage of residents reporting Fair/Poor health? 
  - Answer: ZIP code 92227 in Imperial County, CA, has the highest percentage of individuals reporting 'Fair or Poor Health,' with 24% of the county's residents reporting this status. Furthermore, the top 20 ZIP codes also have very similar '% Fair or Poor Health'. 
  - Visualization: ![Q2 Visualization]

- [+] Question 3: What ZIP code(s) has the highest percentage of Hispanic population?
  - Answer: ZIP codes 91618, 91608, 93043, 93606, 93627, 95724, and 96162 all have a 100% Hispanic residents population.
  - Visualization: ![Q4 Visualization] 


- [+] Question 4: Do ZIP code(s) with higher % Hispanic Residents also report higher % Fair/Poor Health?
  - Answer: After creating a scatterplot and checking for a correlation between "% Hispanic Residents" and "% Fair/Poor Health" by ZIP code, we observed that the scatterplot shows an upward-sloping trend. This suggests that ZIP codes with higher percentages of Hispanic residents tend to also report higher percentages of Fair/Poor Health.
  Running a Pearson correlation, which measures the strength of a linear relationship between two variables (ranging from -1 to +1, where -1 is a negative correlation, 0 is no correlation, and +1 is a perfect positive correlation), we obtained a correlation coefficient of 0.391 with a p-value of 0.000. This indicates a moderate positive correlation that is statistically significant, meaning the observed relationship is unlikely due to random chance. In other words, ZIP codes with higher percentages of Hispanic residents tend to have somewhat higher percentages of residents reporting Fair/Poor Health.
  - Visualization: ![Q3 Visualization]

- [+] Question 5: Which ZIP code(s) reports the highest % of residents with disabilities?
  - Answer: The bar graph reveals that the ZIP code with the highest percentage of residents with disabilities is ZIP code 95587, with 100% of its residents being disabled.
  - Visualization: ![Q5 Visualization]


- [+] Question 6: Do ZIP code(s) with higher % disability also report higher % Fair/Poor Health?
  - Answer: Answer: After creating a scatterplot and checking for a correlation between "% Residents with Disabilities" and "% Fair/Poor Health" by ZIP code, we observed that the scatterplot shows a slight upward-sloping trend. This suggests that ZIP codes with higher percentages of disabled residents tend to also report slightly higher percentages of Fair/Poor Health. 
  Running a Pearson correlation, which measures the strength of a linear relationship between two variables (ranging from -1 to +1, where -1 is a negative correlation, 0 is no correlation, and +1 is a perfect positive correlation), we obtained a correlation coefficient of 0.197 with a p-value of 0.000. This indicates a weak positive correlation that is statistically significant, meaning the observed relationship is unlikely due to random chance. In other words, ZIP codes with higher percentages of disabled residents tend to have somewhat higher percentages of residents reporting Fair/Poor Health, although the effect is weaker than that observed with % Hispanic residents.
  - Visualization: ![Q6 Visualization] 

- [+] Question 7: Which ZIP code(s) report the highest average physically unhealthy days?
  - Answer: The bar graph shows the top 20 ZIP codes by Average Number of Physically Unhealthy Days. 17 of these ZIP codes share the same average value of approximately 4.16 physically unhealthy days, while the remaining three have slightly lower averages (4.1608 days). This indicates that many ZIP codes report very similar levels of physically unhealthy days across the population.
  - Visualization: ![Q7 Visualization] 

- [+] Question 8: Do ZIP codes with higher % Hispanic residents report more physically unhealthy days?
  - Answer: Answer: After creating a scatterplot and checking for a correlation between "% Hispanic Residents" and "Average Number of Physically Unhealthy Days," we observed a slightly upward-sloping trend, suggesting that ZIP codes with higher percentages of Hispanic residents tend to report slightly more physically unhealthy days.
  Running a Pearson correlation, which measures the strength of a linear relationship between two variables (ranging from -1 to +1, where -1 is a perfect negative correlation, 0 is no correlation, and +1 is a perfect positive correlation), we obtained a correlation coefficient of 0.250 with a p-value of 0.000. This indicates a weak positive correlation that is statistically significant, confirming that ZIP codes with higher percentages of Hispanic residents tend to report slightly more physically unhealthy days.
  - Visualization: ![Q8 Visualization] 

- [+] Question 9: : Do ZIP codes with higher % disabled residents report more physically unhealthy days? 
  - Answer: Answer: After creating a scatterplot and checking for a correlation between "% Residents with Disabilities" and "Average Number of Physically Unhealthy Days," we observed an upward-sloping trend, suggesting that ZIP codes with higher percentages of Disabled residents tend to report more physically unhealthy days.
  Running a Pearson correlation, which measures the strength of a linear relationship between two variables (ranging from -1 to +1, where -1 is a perfect negative correlation, 0 is no correlation, and +1 is a perfect positive correlation), we obtained a correlation coefficient of 0.322 with a p-value of 0.000. This indicates a moderate positive correlation that is statistically significant, confirming that ZIP codes with higher percentages of Disabled residents tend to report more physically unhealthy days.
  - Visualization: ![Q9 Visualization]

- [+] Question 10: Do ZIP codes with higher % residents who don’t speak English well report higher % Fair/Poor Health?
  - Answer: After creating a scatterplot and regression line between "% Residents with English Not Well" and "% Fair or Poor Health," we observed a slight upward-sloping trend. This suggests that ZIP codes with higher percentages of residents who do not speak English well tend to report slightly higher percentages of poor or fair health. 
  Running a Pearson correlation, which measures the strength of a linear relationship between two variables (ranging from -1 to +1, where -1 is a negative correlation, 0 is no correlation, and +1 is a perfect positive correlation), we obtained a correlation coefficient of 0.153 with a p-value of 0.000. This indicates a weak positive correlation that is statistically significant, confirming that ZIP codes with higher limited English proficiency tend to report slightly worse health outcomes.
  - Visualization: ![Q10 Visualization] 
