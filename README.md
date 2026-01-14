# Power BI - Employee Retention Risk Analysis

This organization is experiencing disproportionately high employee attrition among certain roles and early-tenure employees. The leadership team is aware of the overall attrition rates, but lack clarity on where the risk is concentrate and the underlying factors contributing to employee turnover. 

The objective of this project is to provide the leadership team with a clear and data driven understanding of attrition patterns across multiple variables. Understanding where attrttion occurs is the first step to understanding why it occurs. With this information, leadership can focus their efforts where improvements will be most impactful. 

The data for this analysis is sourced from Kaggel via a public dataset: 
<p></p>
https://www.kaggle.com/datasets/shubham17mcb1015/hr-data

## Slide 1 - Overview & Analysis

<p></p>

The purpose of Slide 1 is to quickly identify where employee retention challenges are most acute. Here, I establish the scope, scale, and distribution of attrition risk by developing KPI's and level-based views.

<img width="737" height="430" alt="image" src="https://github.com/user-attachments/assets/be41e937-8f00-4bf4-a590-606ee5c35a80" />


<p></p>

Slide 1 will assist in answering the following questions established by the leadership team:

<p></p>

*  How severe is the attrition problem overall?
*  Is attrition concentrated early in employee tenure or evenly over time?
*  What job roles and job levels experience the highest attrition rates?
*  Are certain areas of the organization disproportionately affected?

<p></p>

#### Early Tenure Attrition is Primary Risk Area

<p></p>

The organization's overall attriton rate is 16.12%. While not crisis-level, it does indicate a meaningfull level of staff turnover. Deeper investigation reveals a significant concentration of attrition risk among early-tenure employees with nearly 34.88% of employees leaving within their first year. 

<p></p>

#### Attrition Varies Significantly by Job Role

<p></p>

From the visualizations, it is evident that Sales Representatives experience the highest attrition rates, close to 40%. Laboratory Technicians and Human Resource employees also show elevated attriton rates. Managerial and Director-level roles rates are substancially lower, indicating a significant correlation between attrition rate and job role. 

#### Job Level Reveals Structural Risk Differences:

<p></p>

Attrition is highest at Job Level 1 (26.3%). The organization is experiencing a secondary peak at Job Level 3 (14.7%). Job Levels 4 and 5 show noticebly lower attriton rates, suggesting that career progression and seniority provide a stabilizing effect. 

#### Average Tenure Reflects a Mixed Workforce

<p></p>

The average tenure of 6 years suggest a workforce composed of a core group of longer-tenured employees with a rotating population of newer hires. 


<p></p>

## Slide 1 - Key Takeaways

<p></p>

We can observe from Slide 1 that attrition within the organization is not evenly distributed and that risk is concentrated among:

<p></p>

* Early-tenure employees
* Entry-level roles
* Specific roles including Sales, Lab Techs, and HR employees

## Slide 1 - DAX Formulas

<p></p>

<img width="440" height="272" alt="image" src="https://github.com/user-attachments/assets/6b0dcbab-fbd8-450e-94c4-88046d3fd489" />


<p></p>
 
<img width="440" height="272" alt="image" src="https://github.com/user-attachments/assets/0c738d44-7a7d-4234-8813-bf3a48a71580" />

<p></p>

<img width="440" height="272" alt="image" src="https://github.com/user-attachments/assets/4beed9fa-af74-4069-bf75-78362fde922a" />

<p></p>

## Slide 2 - Overview & Analysis

<p></p>

The purpose of Slide 2 is to identify why attrition occurs. Here we examine how employee experience, workload, and career progression relate to attrition risk. The goal is not to assign causation, but to identify consistent patterns that leadership can use in retention strategies. 

<p></p>

<img width="737" height="432" alt="image" src="https://github.com/user-attachments/assets/3773efdd-a969-4139-a9be-a085f1ff669f" />

<p></p>

#### Satisfaction & Engagement Scores Show Strong Correlation

<p></p>

Satisfaction dimensions 'Job Involvement' and 'Work-Life Balance' show a significant decline in attrition as scores increase. This suggest that these dimensions are especially influential retention signals. Attrition rates are consistently higher among employees who've responded with low scores for all satisfaction dimensions, reinforcing that an employees experience is closely related to retention outcomes.

#### Overtime is a Clear Attrition Risk Indicatcor

<p></p>

Employees that work overtime have substancially higher attrition rates (30%) when compared to employees that do not (10%). This suggest that working overtime amplifies the risk of attrition, especially when combined with satisfaction and engagement stressors. 

<p></p>

#### Promotional Timing Correlates With Attrition Risk

<p></p>

The line chart shows that attrition rates rise as time since last promotion grows. Notably, rates spike when employees have gone several years without a promotion, particularly around the 6-7 year mark. This pattern suggest that career progression is an important factor that influences retention. 

## Slide 2 - Key Takeaways

<p></p>

How employees experience their work at this organization is strongly associated with attriton. Drivers such as satisfaction levels, overtime status, and career progression, likely influence an employees decision to leave the organization. This, when combined with the analysis from Slide 1 help explain attrition rates 

<p></p>

## Slide 2 - DAX Formulas

<p></p>

<img width="440" height="272" alt="image" src="https://github.com/user-attachments/assets/5be4a2db-3d94-4dad-a0d3-ddecc82698b7" />

<p></p>

<img width="440" height="272" alt="image" src="https://github.com/user-attachments/assets/82652e59-f574-4cf8-a6f0-d80602beef9d" />

<p></p>


## 5. Recommendations & Conclusion

<p></p>

This analysis demonstrates that employee attrition within the organization is not random but instead follows clear patterns across job role, employee experience, workload, and career progression. I suggest the leadership team consider the following:

<p></p>

* Review onboarding processes and role expectations
* Monitor and manage 'overtime status' to lower burnout in high-risk roles
* Use satisfaction metrics to guide proactive retention discussions
* Use time since last promotion as a risk flag 

<p></p>







