### Overview

WHO estimates that depression and anxiety cost the global economy $1 trillion annually in lost productivity. Based on this fact, I have decided to analyze employees mental health based on well-being metrics across different industries in the US market. The goal is to gain a broader overview of 
how the recognizion of mental health has evolved over years 2015 to 2023.

The source of the data is US job reviews dataset from Kaggle.
https://www.kaggle.com/datasets/davidgauthier/glassdoor-job-reviews-2
This large dataset (+6 million inputs) contains job descriptions and rankings among various criteria such as work-life balance, compensation, company culture, etc.


<details>

  <summary>Click to see the list of columns in the dataset</summary>

  ### Columns: 
  
  - rating: overall rating given by the employee (e.g., 5.0 out of 5)
  - status: indicates whether the reviewer is a current or former employee.
  - pros: lists the positive aspects of the company or job 
  - cons: lists the negative aspects faced in the company or job
  - recommend: indicates whether the employee would recommend the company to others
  - ceo_approval: reflects the employee’s opinion on the CEO’s leadership
  - career_opportunities: a rating indicating opportunities for professional growth and advancement
  - compensation_and_benefits: a rating reflecting satisfaction with salary, bonuses, and other benefits
  - senior_management: a rating evaluating the performance and effectiveness of senior leadership or management
  - work/life_balance: a rating that assesses how well the company supports balance between work and personal life
  - culture_and_values: a rating reflecting the company’s culture, values, and overall work environment
  - diversity_and_inclusion: a rating indicating the company’s efforts for an inclusive and diverse workplace
  - job: job title of the reviewer providing the feedback
  - year: when the review was submitted
  - firm_name: name of the company being reviewed

</details>

pyproject.toml


### Instructions
All the neccesary libraries for this project can be find in pyproject.toml & lib.txt files.


<details>
  <summary>Notebooks explanation</summary>
  
  - glassdoor_cleaning.ipynb notebook contains scripts for cleaning and preprocessing raw data
  - well_being_analysis.ipynb & job&industries.ipynb contains scripts for analaysis the evolution of well-being metrics over years focusing on particular companies and jobs
  - department_analysis.ipynb contains scripts for analaysis the evolution of well-being metrics over years per industries
  - sentiment_analysis.ipynb has scripts for collect data on overall sentiment & analyze frequently mentioned keywords
  - hypothesis_tesing.ipynb based on our KPI's we are testing the given hypothesis

</details>

### Objectives

- Industries comparison: Analysis across industries over the years, examining correlations with work-life balance and the evolution of mental health indicators
- Text mining: Applied techniques, such as word counting and frequency analysis, to identify the most common terms in employee pros and cons for each industry.
- Sentiment analysis: Analysis on employees' pros and cons using TextBlob and natural language processing (NLP) techniques to assess workplace perceptions.
- Hypothesis testing: Looking for significant dependencies between well-being metrics, burnout & retention applying two sample t-test and correlation matrix.
- Visualizations: Plots with results & trends over years (figures file) & generated wordclouds with most frequent word for pros and cons in sentiment_analysis notebook
- Data: all the filtered data for different visualizations were saved & can be found in data/clean file.

### Key Insights
- Work/life balance has the strongest statistical association with lower stress levels 
- As senior management, culture and values & rating is increasing, burnout level is decreasing
- Higher reports of burnout and anxiety being associated with lower retention rates
- Technology & Education as a leader in the effort of creating a healthier work environment
- Energy as a particularly challenging work environment, with highest stress levels

### Recommendations
1. Accessible mental health services
   - Implement mental health programs & support (eg. regular team check-ups)
   - 💡 lower healthcare costs = addressing mental health reduces absenteeism
  
2. Flexible work policies
   - Hybrid/ remote work if possible, adjust work hours to personal needs
   - 💡employees with good mental health are more productive,  innovative & efficiency

3. Fair compensation & benefits
   - Equal salaries, shares, gym membership, extra days off
   - 💡 higher retention rates decrease turnover, saving recruitment and training costs
  
4. Get inspired
   - Salesforce's /Basecamp well-being programs
   - 💡 free mental health counseling, guided meditation sessions, summer hours from May to October  sabaticals

<details>
  <summary>Sources for case studies</summary>
  - https://www.who.int/teams/mental-health-and-substance-use/promotion-prevention/mental-health-in-the-workplace
  - https://pmc.ncbi.nlm.nih.gov/articles/PMC3698814/
  - https://medium.com/heart-at-work/what-basecamps-ceo-jason-fried-taught-me-about-burnout-simplicity-and-saying-no-8f59441e533e

</details>

### Presentation
[Presentation Slides](### Overview

WHO estimates that depression and anxiety cost the global economy $1 trillion annually in lost productivity. Based on this fact, I have decided to analyze employees mental health based on well-being metrics across different industries in the US market. The goal is to gain a broader overview of 
how the recognizion of mental health has evolved over years 2015 to 2023.

The source of the data is US job reviews dataset from Kaggle.
https://www.kaggle.com/datasets/davidgauthier/glassdoor-job-reviews-2
This large dataset (+6 million inputs) contains job descriptions and rankings among various criteria such as work-life balance, compensation, company culture, etc.


<details>

  <summary>Click to see the list of columns in the dataset</summary>

  ### Columns: 
  
  - rating: overall rating given by the employee (e.g., 5.0 out of 5)
  - status: indicates whether the reviewer is a current or former employee.
  - pros: lists the positive aspects of the company or job 
  - cons: lists the negative aspects faced in the company or job
  - recommend: indicates whether the employee would recommend the company to others
  - ceo_approval: reflects the employee’s opinion on the CEO’s leadership
  - career_opportunities: a rating indicating opportunities for professional growth and advancement
  - compensation_and_benefits: a rating reflecting satisfaction with salary, bonuses, and other benefits
  - senior_management: a rating evaluating the performance and effectiveness of senior leadership or management
  - work/life_balance: a rating that assesses how well the company supports balance between work and personal life
  - culture_and_values: a rating reflecting the company’s culture, values, and overall work environment
  - diversity_and_inclusion: a rating indicating the company’s efforts for an inclusive and diverse workplace
  - job: job title of the reviewer providing the feedback
  - year: when the review was submitted
  - firm_name: name of the company being reviewed

</details>

pyproject.toml


### Instructions
All the neccesary libraries for this project can be find in pyproject.toml & lib.txt files.


<details>
  <summary>Notebooks explanation</summary>
  
  - glassdoor_cleaning.ipynb notebook contains scripts for cleaning and preprocessing raw data
  - well_being_analysis.ipynb & job&industries.ipynb contains scripts for analaysis the evolution of well-being metrics over years focusing on particular companies and jobs
  - department_analysis.ipynb contains scripts for analaysis the evolution of well-being metrics over years per industries
  - sentiment_analysis.ipynb has scripts for collect data on overall sentiment & analyze frequently mentioned keywords
  - hypothesis_tesing.ipynb based on our KPI's we are testing the given hypothesis

</details>

### Objectives

- Industries comparison: Analysis across industries over the years, examining correlations with work-life balance and the evolution of mental health indicators
- Text mining: Applied techniques, such as word counting and frequency analysis, to identify the most common terms in employee pros and cons for each industry.
- Sentiment analysis: Analysis on employees' pros and cons using TextBlob and natural language processing (NLP) techniques to assess workplace perceptions.
- Hypothesis testing: Looking for significant dependencies between well-being metrics, burnout & retention applying two sample t-test and correlation matrix.
- Visualizations: Plots with results & trends over years (figures file) & generated wordclouds with most frequent word for pros and cons in sentiment_analysis notebook
- Data: all the filtered data for different visualizations were saved & can be found in data/clean file.

### Key Insights
- Work/life balance has the strongest statistical association with lower stress levels 
- As senior management, culture and values & rating is increasing, burnout level is decreasing
- Higher reports of burnout and anxiety being associated with lower retention rates
- Technology & Education as a leader in the effort of creating a healthier work environment
- Energy as a particularly challenging work environment, with highest stress levels

### Recommendations
1. Accessible mental health services
   - Implement mental health programs & support (eg. regular team check-ups)
   - 💡 lower healthcare costs = addressing mental health reduces absenteeism
  
2. Flexible work policies
   - Hybrid/ remote work if possible, adjust work hours to personal needs
   - 💡employees with good mental health are more productive,  innovative & efficiency

3. Fair compensation & benefits
   - Equal salaries, shares, gym membership, extra days off
   - 💡 higher retention rates decrease turnover, saving recruitment and training costs
  
4. Get inspired
   - Salesforce's /Basecamp well-being programs
   - 💡 free mental health counseling, guided meditation sessions, summer hours from May to October  sabaticals

<details>
  <summary>Sources for case studies</summary>
  
  - https://www.who.int/teams/mental-health-and-substance-use/promotion-prevention/mental-health-in-the-workplace
  - https://pmc.ncbi.nlm.nih.gov/articles/PMC3698814/
  - https://medium.com/heart-at-work/what-basecamps-ceo-jason-fried-taught-me-about-burnout-simplicity-and-saying-no-8f59441e533e

</details>

### Presentation
[Presentation Slides](https://www.canva.com/design/DAGY6bhs84I/Hkgb_bPwjE8ZO7rhKvnIqA/edit?utm_content=DAGY6bhs84I&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)




