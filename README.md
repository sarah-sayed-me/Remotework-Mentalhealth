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

## 1. Important Numbers
- **Visualization Type**: KPI card
- **Description**: Displays the number of employees categorized by gender (males, females, total), work modality (remote, onsite, hybrid), and satisfaction levels (satisfied, unsatisfied, neutral).
- **Purpose**: Helps compare satisfaction levels across different departments, roles, and work modalities to identify trends and areas for improving remote work policies.

## 2. Industries & Jobs
- **Visualization Type**: Slicers
- **Description**: Filters for selecting specific industries and jobs within the dataset. Users can refine their analysis by choosing one or more industries or job roles.
- **Purpose**: Enhances the interactivity of the dashboard, allowing users to focus on specific sectors or roles for more targeted analysis.
![Screenshot 2024-10-13 130747](https://github.com/user-attachments/assets/d6a52e96-fb06-4f80-8ada-225c03e9aaa7)
## 3. Remote, Hybrid, and Onsite Work by Stress Level
- **Visualization Type**: Clustered column chart
- **Description**: Displays the number of employees by work modality (Remote, Hybrid, Onsite) across different stress levels (High, Medium, Low).
  - High Stress: Remote Work has the highest number of employees.
  - Medium Stress: Employees are relatively similar across modalities.
  - Low Stress: Onsite Work has the highest number of employees.
- **Observation**: Numbers are too close to draw strong conclusions, but remote work shows a tendency toward higher stress levels.
- **Purpose**: Provides insights into the distribution of stress among different work settings.

## 4. Remote, Hybrid, and Onsite Work by Sleep Quality
- **Visualization Type**: Clustered column chart
- **Description**: Illustrates employees by work modality and their sleep quality (Average, Good, Poor).
  - Remote Work shows the highest percentage reporting average sleep.
  - Hybrid Work is associated with good sleep quality.
  - Onsite Work shows a higher percentage of poor sleep quality.
- **Purpose**: Highlights the potential connection between work modality and sleep quality, helping inform decisions to improve employee well-being.

## 5. Remote, Hybrid, and Onsite Work by Life Balance
- **Visualization Type**: Clustered column chart
- **Description**: Shows employees by work modality and their life balance ratings (Poor, Fair, Good, Excellent, Moderate).
  - Remote Work has the highest number of employees reporting poor life balance.
  - Onsite Work is associated with moderate life balance.
  - Hybrid Work shows a balanced distribution across categories.
- **Purpose**: Offers insights into how work modalities impact life balance, informing policies to improve work-life balance.

## 6. Remote, Hybrid, and Onsite Work by Social Isolation
- **Visualization Type**: Clustered column chart
- **Description**: Shows employees by work modality and their ratings of social isolation (Poor, Fair, Good, Excellent, Moderate).
  - Remote Work is associated with poor or fair social isolation.
  - Onsite Work has more employees reporting moderate isolation.
  - Hybrid Work is balanced across categories.
- **Purpose**: Provides insights into social isolation in different work settings, guiding workplace connectivity efforts.

## 7. Slicer: Industry
- **Visualization Type**: Slicer
- **Description**: Allows users to filter data by selecting specific industries for focused analysis.
- **Purpose**: Helps HR and business leaders understand industry-specific trends.

## 8. Slicer: Job Role
- **Visualization Type**: Slicer
- **Description**: Enables users to filter data by selecting specific job roles.
- **Purpose**: Supports job role-specific analysis and insights.
  
   ![Screenshot 2024-10-13 130758](https://github.com/user-attachments/assets/d3107b48-b522-4dda-9c9f-ff6d6ce006dc)
  
## 9. Remote, Hybrid, and Onsite Work by Physical Activity
- **Visualization Type**: Clustered column chart
- **Description**: Displays the number of employees by work modality and physical activity levels (Daily, Weekly, None).
  - Remote Work is associated with higher daily/weekly physical activity.
  - Onsite Work has a slightly higher percentage of employees reporting no activity.
- **Purpose**: Highlights physical activity distribution across work modalities, providing insights for wellness initiatives.

## 10. Remote, Hybrid, and Onsite Work by Mental Health Conditions
- **Visualization Type**: Clustered column chart
- **Description**: Displays employees by work modality and mental health conditions (Anxiety, Burnout, None, Depression).
  - Remote Work is associated with higher mental health concerns.
  - Onsite Work shows a lower percentage of mental health conditions.
- **Purpose**: Provides insights into the mental health distribution in different work settings.

## 11. Remote, Hybrid, and Onsite Work by Productivity Change
- **Visualization Type**: Clustered column chart
- **Description**: Shows productivity changes (Decrease, No Change, Increase) across work modalities.
  - Remote Work shows the highest productivity changes in both the decrease and increase categories.
  - Onsite Work is associated with no change in productivity.
- **Purpose**: Highlights how work modalities affect productivity, providing insights into potential areas for improvement.

## 12. Remote, Hybrid, and Onsite Work by Gender
- **Visualization Type**: Clustered column chart
- **Description**: Displays employees by work modality and gender.
  - Remote and Hybrid Work show similar numbers for productivity increase/decrease.
  - Onsite Work is more associated with no change in productivity.
- **Purpose**: Provides gender-specific insights across work settings.

## 13. Satisfaction by Job Role
- **Visualization Type**: Line chart
- **Description**: Explores the relationship between job roles and employee satisfaction across work modalities.
  - Designers are the most unsatisfied.
  - Sales employees are the most satisfied.
- **Purpose**: Identifies satisfaction trends based on job roles, informing job design improvements.

## 14. Work Modality by Experience Level
- **Visualization Type**: Line chart
- **Description**: Shows work modality by experience level.
  - Early Career: More likely to be in remote work.
  - Mid-Level and Veteran: Tend toward hybrid or onsite work.
- **Purpose**: Highlights trends in work modality allocation based on experience level.

![Screenshot 2024-10-13 130810](https://github.com/user-attachments/assets/747adbc9-9a67-4edc-bca6-85675731148b)

  15. Work Modality by Type of Work
- **Visualization Type**: Line chart
- **Description**: Displays work modality by the type of work (Part-time, Standard Full-time, Extended Full-time, Overtime).
  - Remote Work is dominant for part-time employees.
  - Hybrid Work is more common for full-time employees.
- **Purpose**: Provides insights into work modality distribution by work type, helping to inform flexible work policies.

  16. Company Support for Remote Work by Region
- **Visualization Type**: Clustered column chart
- **Description**: Compares company support for remote work across regions (Oceania, Africa, South America, Europe, Asia, North America).
  - Overall, support is high across all regions, with some variations.
- **Purpose**: Provides global insights into remote work support trends by region.

 17. Work Modality by Meeting Engagement
- **Visualization Type**: Clustered column chart
- **Description**: Displays employee engagement levels in meetings across work modalities.
  - Remote Work is associated with minimal meeting engagement.
  - Hybrid Work shows a more balanced distribution.
- **Purpose**: Offers insights into meeting engagement trends in different work settings.
     
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
![Screenshot 2024-10-15 235950](https://github.com/user-attachments/assets/90a9accd-194d-483e-a6eb-74b51c822cc5)

  19. **Sum of Company Support for Remote Work**
    - **Visualization Type**: Donut chart.
    - **Description**:
      - Displays the total support for remote work across different regions: North America, Asia, Europe, South America, Africa, and Oceania.
      -  North America has the highest support for remote work, followed by Oceania, Africa, and Asia. Europe and South America have the least support.
    -  **Purpose** :
      - To visualize the total support for remote work initiatives across different regions, helping to identify where support is strongest or weakest.
  
 20. **Count of Company Support for Remote Work**
    - **Visualization Type**: Geographic map.
    - **Description**:
      - Shows the geographical distribution of company support for remote work across different regions on a map.
      -   The geographic map effectively highlights where company support for remote work exists. This can aid in understanding regional dynamics and cultural differences regarding remote work preferences.
    -  **Purpose** :
      -To provide a visual representation of geographical support for remote work, enabling quick identification of regional trends.

21.  **Remote Work, Hybrid Work, and Onsite Work by Meeting Level**
    - **Visualization Type**: Donut chart.
    - **Description**:
       - Illustrates the distribution of meeting types (Remote Work, Hybrid Work, and Onsite Work) among different employee categories, with the counts for each type of work.
       -  Remote Work has the highest count of meetings, suggesting it is a popular modality. Hybrid Work follows closely, while Onsite Work has slightly fewer meetings.
     -  **Purpose** :
      -To understand the distribution of work modalities and their relation to meeting types, aiding in workforce planning and resource allocation.

22.  **Key Influencers**
    - **Visualization Type**:  Analytical chart showing relationships.
    - **Description**:
       - An analytical breakdown identifying factors influencing employee satisfaction with remote work, indicating that remote work increases satisfaction by a factor of 1.1x when categorized as neutral.
       - The analysis indicates that having remote work as a work location increases the likelihood of employee satisfaction. The 1.1x factor suggests that while remote work is beneficial, it may not be the sole determinant of satisfaction.
    -  **Purpose** :
      -To analyze and communicate the factors affecting employee satisfaction with remote work, assisting managers in improving remote work policies and practices.

23.  **Q&A**
    - **Visualization Type**: The Q&A feature.
    -  Encourages users to interact with the data by asking specific questions. This interactive element can enhance user engagement and facilitate deeper insights.
    -  **Purpose** :
      -The Q&A section enhances the ability to extract actionable insights from the data, making it easier for decision-makers to understand trends and identify areas for improvement.

     ![Screenshot 2024-10-16 002519](https://github.com/user-attachments/assets/370a0105-0ab5-4611-a12f-18ddf6da6c21)

24. 
- **Visualization Type**: Line chart
- **Description**: Displays work modality by the type of work (Part-time, Standard Full-time, Extended Full-time, Overtime).
  - Remote Work is dominant for part-time employees.
  - Hybrid Work is more common for full-time employees.
- **Purpose**: Provides insights into work modality distribution by work type, helping to inform flexible work policies.


## Key Insights and Findings

### Gender Distribution::
- **[Insight]**: The number of males (1270) and females (1274) in the workforce is nearly equal, indicating balanced gender representation.

### Work Modality Distribution:
- **[Insight]**:Remote work:
  1714 employees
 Onsite work: 1637 employees
 Hybrid work: 1649 employees
 This highlights a relatively even split among the three work modalities, with remote work slightly leading.

### Stress Levels by Work Modality:
- **[Insight]**:Remote work:
  Employees with high stress levels are more likely to work remotely, with lower stress observed in hybrid or onsite work.
  Stress management strategies may be particularly relevant for remote workers.

### Life Balance by Work Modality:
- **[Insight]**:Remote work:
 A higher percentage of employees with excellent life balance are in hybrid work, followed by remote and onsite work.
 Hybrid work seems to offer the best overall life balance.

## Conclusion

### Overall Findings:
The comprehensive analysis has provided valuable insights into various aspects of the business:
- **[Finding 1]**: Remote workers experience higher stress levels and social isolation compared to hybrid or onsite workers.
- **[Finding 2]**: Hybrid work consistently leads to better life balance and satisfaction compared to other modalities, making it a strong contender for an optimal work arrangement.
- **[Finding 3]**: Employee satisfaction is evenly distributed, with significant portions reporting neutral or unsatisfied feelings, signaling areas for improvement in engagement and well-being.

### Impact on the Business:
The insights derived from this analysis can have a significant impact on the business by:
- **[Impact 1]**:Informing HR and leadership teams about how work modalities influence employee well-being, enabling better work policy formulation.
- **[Impact 2]**:Highlighting the need to address stress and isolation issues among remote workers, which could improve retention and productivity.
- **[Impact 3]**:Demonstrating the value of hybrid work arrangements in fostering a balanced and satisfied workforce, which can attract and retain top talent.

### Recommendations:
- **[Recommendation 1]**: Introduce well-being initiatives such as virtual team-building activities and stress management workshops tailored for remote workers.
- **[Recommendation 2]**:Promote hybrid work arrangements to enhance life balance and employee satisfaction, where feasible.
- **[Recommendation 3]**:Conduct role-specific and industry-specific analyses to implement targeted interventions addressing unique challenges for different employee groups.
