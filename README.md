# Mental_health_Survey
Mental health Survey of US States and other Countries
Project Objective:
To analyze a mental health survey dataset in order to:

Understand the prevalence of mental health issues in the workplace.

Identify geographic, demographic, and workplace predictors of mental health challenges.

Explore attitudes and stigma related to discussing mental health at work.

Evaluate the availability of resources and employer support across different regions and companies.

Key Fields:
Demographics: Gender, Country, State, self_employed, Age

Mental Health Info: treatment, family_history, work_interfere

Workplace Context: no_employees, remote_work, tech_company

Support Resources: benefits, seek_help, care_options, wellness_program, leave, anonymity

Attitudes & Stigma: mental_health_consequence, phys_health_consequence, mental_vs_physical, obs_consequence, coworkers, supervisors, mental_health_interview

Data Cleaning & Preparation:
Open-ended gender entries like "Malr", "Cis Male", "femail", "nonbinary", "androgyne" were normalized using .replace() and .str.lower().strip() to create consistent gender categories:

Male Female Non-Binary/Other

Datetime Parsing:
Converted Timestamp to datetime and extracted Year-Month for temporal analysis

Categorical Binning:
Custom bins for age analysis:

#### **Write Problem Statement Here.** #### 

1 - How does the frequency of mental health illness and attitudes towards mental health vary by geographic location?

2 - What are the strongest predictors of mental health illness or certain attitudes towards mental health in the workplace?

#### **Define Your Business Objective?**


**Business Objective:**

**1. Identify Risk Factors for Mental Health Issues:**

Understand who is most likely to struggle with mental health based on demographics (e.g., gender, age, country), work conditions (e.g., remote work, company size), and personal history (e.g., family history).

Predict which employee segments are more likely to require support or treatment.

**2. Measure Attitudes and Stigma Toward Mental Health:**

Assess whether employees feel safe discussing mental health with coworkers or supervisors.

Identify regions or job types where stigma around mental illness is still strong.

**3. Drive Policy and Program Improvements:**
Help HR leaders and executives design better mental health policies by highlighting gaps in existing resources and support.

Recommend where to invest in training, awareness, and care options.


**Long-Term Impact:**

By meeting these objectives, organizations can:

Reduce burnout, absenteeism, and turnover

Improve employee well-being and productivity

Build a culture of mental health support and openness

## **5. Solution to Business Objective**


Ans:

**Provide mental health benefits in all company sizes.**

**Promote supervisor training and wellness programs.**

**Normalize discussion of mental health through open channels.**

**Actionable recommendations for HR and leadership teams.**

**Tangible improvements in workplace culture.**

**Recommendations for employer policy improvements especially in CA under United states and United Kingdom.**


# **Conclusion**

Mens fear most to share their mental health condition with other as compared to women. Infact people fear most when they have any mental patient from their family background, even though they are completely free from mental illness.

In Canada under United States, and UK mental health of the people are very poor. In fact employees fear most to share their mental health condition with the employer, supervisor and coworkers.

Here employer, supervisor need to be more broader minded towards mental patient and introduce more supporting program to reduce burnout, absenteeism,  turnover for improving employee well-being and productivity.




