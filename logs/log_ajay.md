# Weekly/Bi-Weekly Log

## Prompts
Following the [Rose/Bud/Thorn](https://www.panoramaed.com/blog/rose-bud-thorn-activity-and-worksheet#:~:text=%22Rose%2C%20Bud%2C%20Thorn%22%20is%20a%20mindful%20design%2D,day%2C%20week%2C%20or%20month.) model:

### Date: 
Week 10 , Till 03/21/2025

### Number of hours: 
8 - 10 hours

### Rose:
  - Introduction about the student admission funnel in higher education
  - Completed the courses and FERPA training shared by the advisor
  - Discussion about the various data sources like Grad Slate, Grad App, UAnalytics
  - Analyzing the data dumps provided by the advisor
  - Getting to know the data flow in each stage
  - Came up with a final proposal plan to present to Stakeholder and possible student presentation at IShowcase.

### Bud: 
  - Getting a training session on UAnalytics 

### Thorn: 
  - Knowledge gap between Mentor, teammates and individual system administrators.
    
## Additional thought
  - Have to decide about the software that we need to use as a team to analyze the data. Considering options like Tableau , Power BI and/or Python

---

### Date: 
Week 11 ,  03/28/2025

### Number of hours: 
12 hours

### Rose:
  - Proceeding to clean and analyzee the data pulled from  GradApp
  - Went into meeting with Kevin Lundeberg (administrator of UAnalytics system) to gain understanding of report pulls from system.
  - Used python to remove the redacted data and create custom columns that help in analyzing the data
  - Came up with initial visualizations using usable columns.
    
### Bud: 
  - Getting an understanding on what aspects of data gets captured from students, and what is getting used.

### Thorn: 
  - Several columns have personal identifiers - not useful towards trend and pattern analysis.
  - There are some columns whose values need to be explained - need keys for all 3 systems.
    
## Additional thought
  - Leaning toward Tableau and Python for Data visualization and Machine Learning model for feature importance and predictions.

---

### Date:
Week 12 ,  04/04/2025

### Number of hours: 
12 hours

### Rose:
  - Clarified the possible queries answerable from GradApp system durig the call with Tavia
  - Went into detailed analysis on column usability, and pondered about all possible questions that may be answered from the visualizations.
  - List of questions we can answer along with appropriate visualizations for each:

### Application Volume and Timing
1. **How has application volume changed over time?**
   - Line chart of application counts by month/year
   - Bar chart showing yearly comparisons

2. **Are there seasonal patterns in application submissions?**
   - Monthly distribution chart across years
   - Heat map of applications by month and year

### Applicant Demographics
3. **What is the geographic distribution of applicants?**
   - Choropleth map based on address/county data
   - Bar chart of application counts by state/country

4. **How does the proportion of international vs. domestic applicants change over time?**
   - Stacked area chart showing proportions over time
   - Pie charts comparing different time periods

5. **What is the distribution of Arizona residents vs. non-residents?**
   - Pie chart or bar chart showing proportions
   - Line chart showing trends over time

### Academic Background
6. **What is the GPA distribution of applicants?**
   - Histogram of standardized GPAs
   - Box plots comparing GPAs across programs

7. **Which fields of study are most common among applicants?**
   - Bar chart of field of study frequencies
   - Treemap visualization of study fields

8. **Which institutions do most applicants come from?**
   - Bar chart of top referring institutions
   - Network diagram showing institutional connections

### Application Completion
9. **What percentage of applicants complete all application requirements?**
   - Funnel chart showing progression through application steps
   - Stacked bar chart of completion rates over time

10. **How do completion rates vary by demographic factors?**
    - Bar charts comparing completion rates by residency status
    - Grouped bar charts showing completion by international status

11. **Is there a relationship between GPA and application completion?**
    - Scatter plot of GPA vs. completion likelihood
    - Box plots comparing GPAs of complete vs. incomplete applications

### Program-Specific Analysis
12. **Which programs receive the most applications?**
    - Bar chart of application counts by program
    - Treemap of application distribution

13. **Do program preferences differ by applicant demographics?**
    - Grouped bar charts showing program choice by residency status
    - Heat map of program popularity by demographic segment

### Recommendation Patterns
14. **How many recommendations do applicants typically submit?**
    - Histogram of recommendation counts
    - Bar chart showing proportion of applicants with different numbers of recommendations

15. **Is there a correlation between number of recommendations and application completion?**
    - Bar chart showing completion rates by recommendation count
    - Line chart showing relationship between these variables

### Application Process Efficiency
16. **What is the average time between application creation and submission?**
    - Histogram of application duration
    - Box plots showing duration by demographic group

17. **Has the application processing time changed over different terms?**
    - Line chart showing trends in processing time
    - Box plots comparing processing time across terms

### Admission Pipeline Analysis
18. **What factors predict application completion?**
    - Feature importance plot from predictive model
    - Decision tree visualization showing key factors

19. **Can we identify at-risk applicants who might not complete their applications?**
    - ROC curve showing model performance
    - Confusion matrix visualizing prediction accuracy
    
### Bud: 
  - Have a base understanding now of GradApp system.

### Thorn: 
  - Panneer and Tanushree still need approvals to access UAccess Analytics software.
    
## Additional thought
  - Python definitely doable, will try visualizations in Tableau to test feasibility.

---

### Date:
Week 13 ,  04/11/2025

### Number of hours: 
8 hours

### Rose:
      - Key insights from the above analysis and visualizations were shared with Tavia.
      - Most questions deemed to be pertinent, asked Tavia to nail down the most important ones with colleague.
      - Have installed VPN and connected to the UAnalytics
      - Created initial set of visualizations on Tableau
    
### Bud: 
  - Have to understand how to create reports and dashboard using Tableau so that the analysis that have been done so far in Python could be produced in a report/Dashboard format.
    
### Thorn: 
  - Have to find out which data to pull from the UAnalytics so that we can build any informative report.
    
## Additional thought

---

### Date:
Week 14 ,  04/18/2025

### Number of hours: 
2 hours

### Rose:
  - Updated the project planning document with the list of visualizations/questions deemed to be useful.
  - Tavia had a discussion with the Admission Team and prioritized visualtions and analysis from list of questions. List is as follows.
    Application Volume and Timing - Admissions Team Priority
1. **How has application volume changed over time?**
   - Line chart of application counts by month/year
   - Bar chart showing yearly comparisons
2. **Are there seasonal patterns in application submissions?** - Admissions Team Priority
   - Monthly distribution chart across years
   - Heat map of applications by month and year

Applicant Demographics
3. **What is the geographic distribution of applicants?** - Admissions Team Priority
   - Choropleth map based on address/county data
   - Bar chart of application counts by state/country

4. **How does the proportion of international vs. domestic applicants change over time?** - Admissions Team Priority
   - Stacked area chart showing proportions over time
   - Pie charts comparing different time periods
Academic Background - Admissions Team Priority
6. **What is the GPA distribution of applicants?**
   - Histogram of standardized GPAs
   - Box plots comparing GPAs across programs

7. **Which fields of study are most common among applicants?** - Admissions Team Priority
   - Bar chart of field of study frequencies
   - Treemap visualization of study fields

8. **Which institutions do most applicants come from?** - Admissions Team Priority
   - Bar chart of top referring institutions
   - Network diagram showing institutional connections
11. **Is there a relationship between GPA and application completion?** - Admissions Team Priority
    - Scatter plot of GPA vs. completion likelihood
    - Box plots comparing GPAs of complete vs. incomplete applications

Program-Specific Analysis
12. **Which programs receive the most applications?** - Admissions Team Priority
    - Bar chart of application counts by program
    - Treemap of application distribution
Admission Pipeline Analysis
18. **What factors predict application completion?** - Admissions Team Priority
    - Feature importance plot from predictive model
    - Decision tree visualization showing key factors
           
### Bud: 
  - Tableau trial account created.
  - Initial visualizations created.
    
### Thorn: 
  - Dashboards seem to be limited in the amount of visualizations supported in each.
  - Need to discuss comparative performances of Python viz and Tableau visualizations to finalize plan.
    
## Additional thought

---
