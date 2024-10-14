# Project Title: Remote work & Mentalhealth

## Project Overview

### Project Title: Remote work & Mentalhealth

### Project Description:
In this dashboard, we aim to analyze the effects of remote work on employees' mental well-being by identifying key metrics such as stress levels, work-life balance, and mental health conditions. The dashboard also explores how factors like industry, job role, and work location (remote, hybrid, or onsite) influence employee satisfaction and productivity.
### Business Objectives:
- understand the affect od remote work in mentalhealth
- Identify trends in job satisfaction and productivity across various work settings.
- Provide actionable insights for HR professionals and businesses to optimize remote work policies.

### Stakeholders:
- HR Manager 
- Business leaders
- Mental health professionals

## Data Sources

### Data Origin:
Data for this project is sourced from a global survey of employees across various industries, capturing insights on their work experiences, mental well-being, and job satisfaction.

### Data Files:
- Employee Survey Data: This file contains comprehensive data on employees' demographics, work settings, mental health, and satisfaction levels.
- Employee_ID
-  Age
-  Gender
-  Job_Role
-  Industry
-  Work_Location (Remote, Hybrid, Onsite)
-  Stress_Level
-  Mental_Health_Condition (e.g., Anxiety, Depression)
-  Social_Isolation_Rating
-  Satisfaction_with_Remote_Work
-  Sleep_Quality
-  Productivity_Change.
-  Work_life_balance
-  Region
-  Number_of_virtual_meeting.
-  Hours_worked_per_week
-  Years_of_experience

## Data Cleaning:
- **Remove Inconsistencies**: Address discrepancies in data entries to ensure uniformity.
- **Handle Missing Values**: Manage missing or incomplete data to maintain analysis accuracy.
- **Standardize Data Formats**: Ensure consistency in the formatting of dates, numbers, and text fields.
- **Validate Data Accuracy**: Cross-check data entries against the source to correct errors.
##Data Transformation:
###Creating conditional columns:
 1.**ExperienceLevel**:
   include conditional column to categories years of experience based on data.
  .Categories:
  - Entry_level : 1-5 years.
  - Early_career: 5-10 years.
  - Mid_career: 10-15 years.
  - Experienced : 15-20 years.
  - Senior_professional : 20-25 years.
  - Advanced_professional : 25-30 years.
  - Veteran : +30 years.
  2. **WorkType**:
    include conditional column to categories Hours worked per week based on data.
    . Categories:
    - Part_time : 20-30 hours.
    - Standard_full_time : 30-40 hours.
    - extented_full_time : 40-50 hours.
    - Overtime : +50 hours.
  3.**SocialIsolation**:
    include conditional column to categories Social_Isolation_Rating based on data.
      . Categories:
      - Not_isolated : 1 .
      - Slightly_isolated : 2 .
      - Moderate_isolated : 3.
      - Highly_isolated : 4.
      - Exteremly_isolated : 5.
  4.**LifeBalance**:
    include conditional column to categories Work_life_balance based on data.
       . Categories:
      - Poor : 1 .
      - Fair : 2 .
      - Moderate : 3.
      - Good : 4.
      - Excellent : 5.
  5.**MeetingLevel**
    include conditional column to categories Number_of_virtual_meeting based on data.
       . Categories:
      - Minimal_engagement : 1-5 .
      - Moderate_engagement: 5-10.
      - High_engagement : 10-15.
  - ## Visualization & Reporting:
![Screenshot 2024-10-13 130734](https://github.com/user-attachments/assets/297ca90c-55f1-4476-9361-ffb85b44d865)

1. **Important Numbers**
   - **Visualization Type**: KPI card
   - **Description**: It displays the number of employees in each category (males, females, total), their work modality (remote, onsite, hybrid), and their reported satisfaction levels (satisfied, unsatisfied, neutral).
   - **Purpose**: comparing satisfaction levels across different departments, roles, and work modalities, it helps identify potential trends, disparities, and areas for improvement in remote work policies and practices.

2. **Industried & Jobs **
   - **Visualization Type**: Slicers
   - **Description**:This slicer displays filters for selecting specific industries and jobs within the dataset. Users can choose one or multiple options to refine their analysis, allowing them to focus on particular sectors or job roles.
   - **Purpose**:The purpose of these slicers is to enhance interactivity and usability within the dashboard. By enabling users to filter by specific industry or job, they can easily compare different segments and gain insights tailored to their interests or needs. This functionality supports more targeted analyses, helping users identify trends, patterns, and differences across various industries and job classifications.
![Screenshot 2024-10-13 130747](https://github.com/user-attachments/assets/d6a52e96-fb06-4f80-8ada-225c03e9aaa7)

3. **RemoteWork,HypirdWork and OnsiteWork by Stress_Level**
   - **Visualization Type**:Clustered column chart
   - **Description**:
   his visualization displays the number of employees categorized by their work modality (Remote Work, Hybrid Work, and Onsite Work) across different stress levels (High, Medium, and Low).
     The findings are as follows:
    a. High Stress: Remote Work has the highest number of employees, followed  by Hybrid Work and Onsite Work.
    b. Medium Stress: The number of employees is relatively similar across all three work modalities.
    c. Low Stress: Onsite Work has the highest number of employees, followed by Hybrid Work and Remote Work.
- **Observations**
. Number are too close to each other.
- The number of employees in each stress level is quite similar across the different work modalities, making it difficult to draw strong conclusions about the relationship between work modality and stress.
- Remote Work is associated with higher levels of stress compared to Onsite Work, particularly in the High Stress category.
   - **Purpose**:
     This visualization aims to shed light on the distribution of stress levels among employees in different work environments, offering insights into employee well-being and potential areas for intervention or 
      support

4. **RemoteWork,HypirdWork and OnsiteWork by Sleep_Quality**
   - **Visualization Type**:Clustered column chart
   - **Description**:
  This visualization illustrates the number of employees across different work modalities (Remote Work, Hybrid Work, and Onsite Work) categorized by their sleep quality (Average, Good, and Poor).
    The findings are as follows:
     a. Average Sleep: Remote Work has the highest number of employees, followed by Onsite Work and Hybrid Work.
     b. Good Sleep: Hybrid Work has the highest number of employees, followed by Remote Work and Onsite Work.
     c. Poor Sleep: Onsite Work has the highest number of employees, followed by Remote Work and Hybrid Work.
  - **Obsevation**:
- While there are slight differences in sleep quality distribution across work modalities, the overall trends are similar, suggesting that sleep quality is not strongly influenced by the specific work setting.
- Remote Work is associated with a higher percentage of employees reporting average sleep quality.
- Hybrid Work is associated with a higher percentage of employees reporting good sleep quality.
- Onsite Work is associated with a higher percentage of employees reporting poor sleep quality.

   - **Purpose**:
      This visualization highlights the distribution of sleep quality across various work settings, providing insights into employee well-being and potential areas for enhancing work-life balance.
     
5. **RemoteWork,HypirdWork and OnsiteWork by LifeBalance**
   - **Visualization Type**:Clustered column chart
   - **Description**:
     This visualization presents the distribution of employees across different work modalities (Remote Work, Hybrid Work, and Onsite Work) categorized by their life balance ratings (Poor, Fair, Good, Excellent, and Moderate). The findings are summarized as follows:
     we find that in Poor level category number of:
     a. Poor Life Balance: Remote Work has the highest number of employees, followed by Onsite Work and Hybrid Work.
     b. Good Life Balance: The number of employees is relatively similar across all three work modalities.
     c. Excellent Life Balance: The number of employees is relatively similar across all three work modalities.
     d. Moderate Life Balance: Onsite Work has the highest number of employees, followed by Hybrid Work and Remote Work.
     e. Fair Life Balance: Remote Work has the highest number of employees, followed by Onsite Work and Hybrid Work.
**Observation**
. While there are slight differences in life balance distribution across work modalities, the overall trends are similar, suggesting that life balance is not strongly influenced by the specific work setting.
. Remote Work has the highest number of employees reporting Poor life balance and the lowest in the Fair category.
. Onsite Work is associated with a higher percentage of employees reporting moderate life balance.
. Hybrid Work shows a relatively balanced distribution across the different life balance categories.
   - **Purpose**:
     This visualization highlights the distribution of life balance across different work modalities, providing valuable insights into employee well-being and areas for potential improvement in work-life balance policies.

6.  **RemoteWork,HypirdWork and OnsiteWork by SocialIsolation**
   - **Visualization Type**:Clustered column chart
   - **Description**:
     This visualization illustrates the distribution of employees across different work modalities (Remote Work, Hybrid Work, and Onsite Work) based on their ratings of social isolation (Poor, Fair, Good, Excellent, and Moderate). The findings are summarized as follows:
     we find that in Poor level category number of:
     a. Poor Social Isolation: Remote Work has the highest number of employees, followed by Onsite Work and Hybrid Work.
     b. Good Social Isolation: The number of employees is relatively similar across all three work modalities.
     c. Excellent Social Isolation: The number of employees is relatively similar across all three work modalities.
     d. Moderate Social Isolation: Onsite Work has the highest number of employees, followed by Hybrid Work and Remote Work.
     e. Fair Social Isolation: Remote Work has the highest number of employees, followed by Onsite Work and Hybrid Work.
- **Observation**
. While there are slight differences in social isolation distribution across work modalities, the overall trends are similar, suggesting that social isolation is not strongly influenced by the specific work setting.
. Remote Work is associated with a higher percentage of employees reporting poor or fair social isolation.Remote Work has the highest number of employees reporting Poor social isolation and the lowest in the Fair category.
. Onsite Work is associated with a higher percentage of employees reporting moderate social isolation.
. Hybrid Work shows a relatively balanced distribution across the different social isolation categories.
   - **Purpose**:
     This visualization highlights the distribution of social isolation experiences across different work modalities, providing valuable insights into employee social well-being and areas for potential improvement in workplace connectivity and support.
     
 7. **Indusrty**
      - **Visualization Type**: Slicer.
      - **Description**:
        fThis slicer enables users to filter data by selecting specific industries, allowing a focused analysis on the chosen sector
      -  **Purpose** :
        The slicer helps determine and display results for a specific industry. It supports HR professionals and business leaders in understanding industry-specific trends and insights.

8. **job**
    - **Visualization Type**: Slicer.
      - **Description**:
        fThis slicer enables users to filter data by selecting specific job roles, allowing a focused analysis on the chosen sector
      -  **Purpose** :
        The slicer helps determine and display results for a specific job role , It supports HR professionals and business leaders in understanding Job role-specific trends and insights.
   ![Screenshot 2024-10-13 130758](https://github.com/user-attachments/assets/d3107b48-b522-4dda-9c9f-ff6d6ce006dc)
9 . **RemoteWork,HypirdWork and OnsiteWork by Physical_Activity**
   - **Visualization Type**:Clustered column chart
   - **Description**:
   This visualization displays the number of employees categorized by their work modality (Remote Work, Hybrid Work, and Onsite Work) across different Physical_activity levels (Daily,Weekly,None).
   The findings are as follows:
     a. Daily Physical Activity: Remote Work has the highest number of employees, followed by Hybrid Work and Onsite Work.
     b. Weekly Physical Activity: Hybrid Work has the highest number of employees, followed by Remote Work and Onsite Work.
     c. No Physical Activity: Remote Work has the highest number of employees, followed by Hybrid Work and Onsite Work.
- **Observations**
. While there are slight differences in physical activity distribution across work modalities, the overall trends are similar, suggesting that physical activity levels are not strongly influenced by the specific work setting..
.Remote Work is associated with a higher percentage of employees engaging in daily or weekly physical activity.
. Onsite Work shows a slightly higher percentage of employees reporting no physical activity.
   - **Purpose**:
     This visualization highlights the distribution of Physical_activity levels across different work settings, providing insights into employee well-being and potential areas for intervention or support.
     
10 . **RemoteWork,HypirdWork and OnsiteWork by Mental_Health_Conditions**
   - **Visualization Type**:Clustered column chart
   - **Description**:
   This visualization displays the number of employees categorized by their work modality (Remote Work, Hybrid Work, and Onsite Work) across different Mental_Health_Conditions levels (Anxiety,Burnout,None,Depression).
The findings are as follows:
     we find that in Anxiety level Mental_Health_Conditions category number of:
     a. Anxiety: Remote Work has the highest number of employees, followed by Hybrid Work and Onsite Work.
     b. Burnout: Remote Work has the highest number of employees, followed by Onsite Work and Hybrid Work.
     c. None: Remote Work has the highest number of employees, followed by Hybrid Work and Onsite Work.
     d. Depression: Remote Work has the highest number of employees, followed by Hybrid Work and Onsite Work.
- **Observations**
. Number are too close to each other.
.  Remote Work is associated with a higher percentage of employees reporting various mental health conditions.
.  Onsite Work shows a slightly lower percentage of employees reporting mental health conditions, particularly anxiety and burnout.
   - **Purpose**:
     This visualization highlights the distribution of Mental_Health_Conditions levels across different work settings, providing insights into employee well-being and potential areas for intervention or support.
     
 11. **RemoteWork,HypirdWork and OnsiteWork by Productivity_Change**
   - **Visualization Type**:Clustered column chart
   - **Description**:
   This visualization displays the number of employees categorized by their work modality (Remote Work, Hybrid Work, and Onsite Work) across different Productivity_Change levels (Decrease, No Change , Increase ).
   The findings are as follows:
     we find that in Decrease level Productivity_Change category number of:
     1. RemoteWork : 588.
     2. Hypird Work : 591.
     3. OnsiteWork : 558.
     we find that in  No Change level Productivity_Change category number of:
     1. RemoteWork : 568.
     2. Hypird Work : 544.
     3. OnsiteWork : 565.
     we find that in Increase level Productivity_Change category number of:
     1. RemoteWork : 558.
     2. Hypird Work : 514.
     3. OnsiteWork : 514.
- **Observations**
. Number are too close to each other.
. Remote Work has the highest number of employees in the Decrease & Increase Productivity_Change category and the lowest in the No Change Physical_activity category.
. Hybrid Work also shows the maximum number in the Deacrese Productivity_Change level and the minimum in the Increase Productivity_Change level.
. Onsite Work has the highest representation in the No Change Productivity_Change category, with the fewest employees in the Increase Productivity_Change category.
   - **Purpose**:
     This visualization highlights the distribution of Productivity_Change levels across different work settings, providing insights into employee well-being and potential areas for intervention or support.

12. **RemoteWork,HypirdWork and OnsiteWork by Gender**
   - **Visualization Type**:Clustered column chart
   - **Description**:
   This visualization displays the number of employees categorized by their work modality (Remote Work, Hybrid Work, and Onsite Work) across different Gender levels (Female, Male,Perfer not to say , Non-binary ).
   The findings are as follows:
     we find that in Female level Gender category number of:
      a. Decrease in Productivity: Remote Work and Hybrid Work have similar numbers of employees, followed by Onsite Work.
      b. No Change in Productivity: Onsite Work has the highest number of employees, followed by Remote Work and Hybrid Work.
      c. Increase in Productivity: Remote Work and Hybrid Work have similar numbers of employees, followed by Onsite Work.
- **Observations**
. Number are too close to each other.
. Remote Work and Hybrid Work are associated with a higher percentage of employees reporting a decrease or increase in productivity.
. Onsite Work is associated with a higher percentage of employees reporting no change in productivity.
   - **Purpose**:
     This visualization highlights the distribution of Gender levels across different work settings, providing insights into employee well-being and potential areas for intervention or support.

 13 . **Indusrty**
      - **Visualization Type**: Slicer.
      - **Description**:
        fThis slicer enables users to filter data by selecting specific industries, allowing a focused analysis on the chosen sector
      -  **Purpose** :
        The slicer helps determine and display results for a specific industry. It supports HR professionals and business leaders in understanding industry-specific trends and insights.

14. **job**
    - **Visualization Type**: Slicer.
      - **Description**:
        fThis slicer enables users to filter data by selecting specific job roles, allowing a focused analysis on the chosen sector
      -  **Purpose** :
        The slicer helps determine and display results for a specific job role , It supports HR professionals and business leaders in understanding Job role-specific trends and insights.
     
![Screenshot 2024-10-13 130810](https://github.com/user-attachments/assets/747adbc9-9a67-4edc-bca6-85675731148b)

15. **Unsatisfied , Satisfied and neutral by Job Role**
   - **Visualization Type**:Line chart
   - **Description**:
   This visualization explores the relationship between job roles and employee satisfaction across different work modalities. The x-axis represents various job roles, while the y-axis represents employee satisfaction levels (Unsatisfied, Satisfied, and Neutral).
a. Designers are the most unsatisfied category.
b. Sales are the most satisfied category.
c. Project managers are the most netral category.
- **Observations**
. The differences in satisfaction levels between job roles are more pronounced than the differences between work modalities.
. Some job roles, such as designers, consistently exhibit lower satisfaction levels regardless of work modality.
   - **Purpose**:
     This visualization aims to identify how job roles and work modalities interact to influence employee satisfaction, providing insights into potential areas for improvement in job design or work environment to enhance overall employee well-being.
     
16. **RemoteWork, HybridWork, and OnsiteWork by ExperienceLevel**
   - **Visualization Type**:Line chart
   - **Description**:
   This visualization explores the relationship between employees categorized by their work modality (Remote Work, Hybrid Work, and Onsite Work) across different ExperienceLevel.
 The x-axis represents various ExperienceLevel, while the y-axis represents  employees categorized by their work modality (Remote Work, Hybrid Work, and Onsite Work).
a. Early Career: Employees in the Early Career stage are more likely to be assigned to Remote Work compared to later stages. 
b. Mid-Level and Veteran: Employees at these levels tend to have a higher representation in Hybrid Work and Onsite Work compared to earlier stages.
c. Experienced: This group shows a relatively balanced distribution across work modalities.
- **Observations**
.The choice of work modality seems to be influenced by experience level.
. As employees gain experience, they are more likely to be assigned to Hybrid or Onsite roles, potentially due to increased responsibilities or the need for in-person collaboration.
   - **Purpose**:
     This visualization provides insights into the distribution of work modalities across different experience levels, highlighting potential trends in career progression and the allocation of work tasks. It can inform HR policies related to talent development and work assignments.

 17. **Remote Work, Hybrid Work, and Onsite Work by Type of Work**
   - **Visualization Type**:Line chart
   - **Description**:
   This visualization explores the relationship between the type of work (Part-time, Standard Full-time, Extended Full-time, Overtime) and the distribution of employees across different work modalities (Remote Work, Hybrid Work, and Onsite Work).
a. Part-time: Remote Work is the dominant work modality, with a significantly higher number of employees compared to Hybrid or Onsite Work.
b. Standard Full-time: Hybrid Work has the highest representation, followed by Remote Work and Onsite Work.
c. Extended Full-time: Remote Work and Hybrid Work have similar levels, with Onsite Work being the least common.
d. Overtime: Remote Work is the most common, followed by Hybrid Work and Onsite Work.
- **Observations**
. The choice of work modality seems to be influenced by the type of work.
. Part-time work is strongly associated with Remote Work, while Standard Full-time and Extended Full-time roles have a more balanced distribution across modalities.
. Overtime work is also more frequently associated with Remote Work.
   - **Purpose**:
     This visualization provides insights into the distribution of work modalities across different types of work, highlighting potential trends in the allocation of tasks and the relationship between work hours and work arrangements. It can inform HR policies related to work flexibility and job design.
     
 18 . **Indusrty**
      - **Visualization Type**: Slicer.
      - **Description**:
        fThis slicer enables users to filter data by selecting specific industries, allowing a focused analysis on the chosen sector
      -  **Purpose** :
        The slicer helps determine and display results for a specific industry. It supports HR professionals and business leaders in understanding industry-specific trends and insights.

19. **job**
    - **Visualization Type**: Slicer.
    - **Description**:
        This slicer enables users to filter data by selecting specific job roles, allowing a 
      focused analysis on the chosen sector
      -  **Purpose** :
        The slicer helps determine and display results for a specific job role , It supports 
        HR professionals and business leaders in understanding Job role-specific trends and insights.

 ![Screenshot 2024-10-14 231810](https://github.com/user-attachments/assets/d2cf7bb3-91c3-4534-9d91-ab84834ec420)

 20 . **Sum of Company_Support_for_Remote_Work by Region**
     - **Visualization Type**:Clustered column chart
     - **Description**:
  This visualization compares the level of company support for remote work across different regions (Oceania, Africa, South America, Europe, Asia, North America).
     a. Regional Variations: There are slight variations in company support, with Oceania and Africa showing slightly higher levels compared to other regions.
    b. Overall High Support: Across all regions, there is a significant level of company support for remote work.
   - **Observations**
   . The differences between regions are relatively small, suggesting that company support for remote work is becoming more widespread.
   . Factors specific to each region (e.g., cultural norms, economic conditions, technological infrastructure) may influence the level of support.
   - **Purpose**:
     This visualization provides insights into the global trends in company support for remote work, highlighting regional differences and potential factors influencing these variations. It can inform HR professionals and business leaders in understanding the evolving landscape of remote work policies and practices.

 21 . **Remote Work, Hybrid Work, and Onsite Work by Meeting Level**
       - **Visualization Type**:Clustered column chart
       - **Description**:
  This visualization compares the number of employees in different work modalities (Remote Work, Hybrid Work, and Onsite Work) based on their level of meeting engagement (Minimal, High, Moderate).
     a. Minimal Engagement: Remote Work has the highest number of employees, followed by 
       Hybrid Work and Onsite Work.
     b.High Engagement: Hybrid Work has the highest number of employees, followed by Remote 
       Work and Onsite Work.
     c. Moderate Engagement: Hybrid Work has the highest number of employees, followed by 
        Remote Work and Onsite Work.
    - **Observations**
    . While there are slight differences in meeting engagement distribution across work modalities, the overall trends are similar, suggesting that meeting engagement is not strongly influenced by the specific work setting.
    . Remote Work is associated with a higher percentage of employees reporting minimal engagement.
    . Hybrid Work shows a relatively balanced distribution across meeting engagement levels.
    . Onsite Work is associated with a slightly higher percentage of employees reporting high engagement.
   - **Purpose**:
     This visualization aims to explore the relationship between work modality and meeting engagement, providing insights into employee communication patterns and potential strategies to optimize virtual meetings in different work environments.

     

## Key Insights and Findings

### [Insight Area 1]:
- **[Insight]**: [Summarize a key insight from your analysis].
- **[Actionable Strategy]**: [Describe the potential strategies or actions based on this insight].

### [Insight Area 2]:
- **[Insight]**: [Summarize a key insight from your analysis].
- **[Actionable Strategy]**: [Describe the potential strategies or actions based on this insight].

[... Repeat for each insight area ...]

## Conclusion

### Overall Findings:
The comprehensive analysis has provided valuable insights into various aspects of the business:
- **[Finding 1]**: [Summarize key finding].
- **[Finding 2]**: [Summarize key finding].
- **[Finding 3]**: [Summarize key finding].

### Impact on the Business:
The insights derived from this analysis can have a significant impact on the business by:
- **[Impact 1]**: [Explain the impact].
- **[Impact 2]**: [Explain the impact].
- **[Impact 3]**: [Explain the impact].

### Recommendations:
- **[Recommendation 1]**: [Briefly describe your recommendation].
- **[Recommendation 2]**: [Briefly describe your recommendation].
- **[Recommendation 3]**: [Briefly describe your recommendation].
