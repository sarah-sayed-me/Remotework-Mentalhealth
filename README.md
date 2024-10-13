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
   his visualization displays the number of employees categorized by their work modality (Remote Work, Hybrid Work, and Onsite Work) across different stress levels (High, Medium, and Low). The findings are as follows:
     we find that in High level stress category number of:
     1. RemoteWork : 590.
     2. Hypird Work : 561.
     3. OnsiteWork : 535.
     we find that in Medium level stress category number of:
     1. RemoteWork : 577.
     2. Hypird Work : 545.
     3. OnsiteWork : 547.
     we find that in Low level stress category number of:
     1. RemoteWork : 547.
     2. Hypird Work : 543.
     3. OnsiteWork : 555.
- **Observations**
. Number are too close to each other.
. Remote Work has the highest number of employees in the High Stress category and the lowest in the Low Stress category.
. Hybrid Work also shows the maximum number in the High Stress level and the minimum in the Low Stress level.
. Onsite Work has the highest representation in the Low Stress category, with the fewest employees in the High Stress category.
   - **Purpose**:
     This visualization highlights the distribution of stress levels across different work settings, providing insights into employee well-being and potential areas for intervention or support.

4. **RemoteWork,HypirdWork and OnsiteWork by Sleep_Quality**
   - **Visualization Type**:Clustered column chart
   - **Description**:
  This visualization illustrates the number of employees across different work modalities (Remote Work, Hybrid Work, and Onsite Work) categorized by their sleep quality (Average, Good, and Poor). The findings are as follows:
     we find that in Average level category number of:
     1. RemoteWork : 582.
     2. Hypird Work : 518.
     3. OnsiteWork : 528.
     we find that in Good level category number of:
     1. RemoteWork : 566.
     2. Hypird Work : 567.
     3. OnsiteWork : 554.
     we find that in poor level category number of:
     1. RemoteWork : 566.
     2. Hypird Work : 564.
     3. OnsiteWork : 555.
  - **Obsevation**:
. The numbers are closely aligned across work modalities, suggesting similar sleep quality experiences among employees in different settings.
. Remote Work shows the highest number of employees in the Average sleep quality category, with consistent figures in both the Poor and Good categories.
. Hybrid Work has the highest number of employees in the Good sleep quality category, while the lowest is found in the Average sleep quality category.
. Onsite Work has the most employees reporting Poor sleep quality and the least in the Average category.

   - **Purpose**:
      This visualization highlights the distribution of sleep quality across various work settings, providing insights into employee well-being and potential areas for enhancing work-life balance.
     
5. **RemoteWork,HypirdWork and OnsiteWork by LifeBalance**
   - **Visualization Type**:Clustered column chart
   - **Description**:
     This visualization presents the distribution of employees across different work modalities (Remote Work, Hybrid Work, and Onsite Work) categorized by their life balance ratings (Poor, Fair, Good, Excellent, and Moderate). The findings are summarized as follows:
     we find that in Poor level category number of:
     1. RemoteWork : 368.
     2. Hypird Work : 322.
     3. OnsiteWork : 333.
     we find that in Good level category number of:
     1. RemoteWork : 347.
     2. Hypird Work : 323.
     3. OnsiteWork : 310.
     we find that in Excellent level category number of:
     1. RemoteWork : 340.
     2. Hypird Work : 338.
     3. OnsiteWork : 299.
     we find that in Moderate level category number of:
     1. RemoteWork : 339.
     2. Hypird Work : 348.
     3. OnsiteWork : 366.
     we find that in Fair level category number of:
     1. RemoteWork : 320.
     2. Hypird Work : 318.
     3. OnsiteWork : 329.
**Observation**
. The numbers across the different life balance ratings are relatively close to each other, indicating similar experiences among employees in various work settings.
. Remote Work has the highest number of employees reporting Poor life balance and the lowest in the Fair category.
. Hybrid Work shows the highest number in the Moderate life balance category, while the Fair category has the least number of employees.
. Onsite Work has the most employees in the Moderate life balance category and the least in the Excellent category.
   - **Purpose**:
     This visualization highlights the distribution of life balance across different work modalities, providing valuable insights into employee well-being and areas for potential improvement in work-life balance policies.

6.  **RemoteWork,HypirdWork and OnsiteWork by SocialIsolation**
   - **Visualization Type**:Clustered column chart
   - **Description**:
     This visualization illustrates the distribution of employees across different work modalities (Remote Work, Hybrid Work, and Onsite Work) based on their ratings of social isolation (Poor, Fair, Good, Excellent, and Moderate). The findings are summarized as follows:
     we find that in Poor level category number of:
     1. RemoteWork : 368.
     2. Hypird Work : 322.
     3. OnsiteWork : 333.
     we find that in Good level category number of:
     1. RemoteWork : 347.
     2. Hypird Work : 323.
     3. OnsiteWork : 310.
     we find that in Excellent level category number of:
     1. RemoteWork : 340.
     2. Hypird Work : 338.
     3. OnsiteWork : 299.
     we find that in Moderate level category number of:
     1. RemoteWork : 339.
     2. Hypird Work : 348.
     3. OnsiteWork : 366.
     we find that in Fair level category number of:
     1. RemoteWork : 320.
     2. Hypird Work : 318.
     3. OnsiteWork : 329.
- **Observation**
. The numbers across different social isolation ratings are relatively close, indicating similar experiences among employees in various work settings.
. Remote Work has the highest number of employees reporting Poor social isolation and the lowest in the Fair category.
. Hybrid Work shows the highest number in the Moderate social isolation category, while it has the least in the Fair category.
. Onsite Work has the most employees in the Moderate social isolation category and the least in the Excellent category.
   - **Purpose**:
     This visualization highlights the distribution of social isolation experiences across different work modalities, providing valuable insights into employee social well-being and areas for potential improvement in workplace connectivity and support.

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
