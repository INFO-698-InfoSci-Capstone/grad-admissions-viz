# Weekly/Bi-Weekly Log

---

### Date:  
**Week 1**, 02/17/2025

### Number of hours:  
3–4 hours

###  Rose:
- Formed the capstone team and understood what teammembers bring to the table.
- Initial project requirements and other technical requirements were checked.

###  Bud:
- Curious to learn more about how graduate admissions data flows through the systems and how it can be visualized.

###  Thorn:
- Had some ambiguity on access protocols and structure of data repositories.

## Additional thought:
- Setting up a shared folder and workspace would streamline upcoming collaboration.

---

### Date:  
**Week 2**, 02/27/2025

### Number of hours:  
4–5 hours

###  Rose:
- First formal meeting with project advisor (Tavia) to discuss project objectives and stakeholder expectations.
- Clarified roles, deliverables, and expectations with project stakeholders.

###  Bud:
- Looking forward to accessing real datasets and diving into exploratory analysis.

###  Thorn:
- Tools for accessing the databases still unclear — needed FERPA training and VPN setup guidance.

## Additional thought:
- Consider documenting system diagrams for GradApp and UAnalytics for onboarding purposes.

---

### Date:  
**Week 3**, 03/03/2025

### Number of hours:  
6 hours

###  Rose:
- Completed FERPA certification.
- Requested data from UAccess and GradApp.
- Discussed UAIR and the challenges with raw admissions data formats.

###  Bud:
- Begin analyzing data dump and planning questions for the dashboard.

###  Thorn:
- No access yet to full UAccess dashboards; awaiting approval for some teammates.

## Additional thought:
- Start listing key variables to track across systems to avoid confusion.

---

### Date:  
**Week 4**, 03/06/2025

### Number of hours:  
8 hours

###  Rose:
- Received the first UAnalytics data dump.
- Skimmed dataset structure, began assessing redacted columns.
- Started basic exploratory analysis using Google Colab.

###  Bud:
- Eager to start creating initial visualizations and identify gaps in the data.

###  Thorn:
- Many columns contain redacted data or require cleaning; need to build preprocessing functions.

## Additional thought:
- Develop a reusable cleaning script for repetitive formatting issues.

---

### Date:  
**Week 5**, 03/14/2025

### Number of hours:  
10 hours

###  Rose:
- Created small visualizations (GPA histogram, application trends).
- Brainstormed a list of possible insights/questions with team.
- Aligned visual goals with the admissions funnel stages.

###  Bud:
- Excited about mapping student flow (applicant → admitted → enrolled) as a funnel view.

###  Thorn:
- Unclear mappings for several coded variables — unsure what some fields represent.

## Additional thought:
- Need to reach out to data analysts like Kevin to decode column meanings.

---

### Date:  
**Week 6**, 03/21/2025

### Number of hours:  
10–12 hours

###  Rose:
- Met with Kevin (Enrollment Management) to clarify UAnalytics structure.
- Got clarity on report pull methods and backend logic.
- Updated project proposal and visual question roadmap.

###  Bud:
- Looking forward to building first prototype dashboards.

###  Thorn:
- GradApp and UAnalytics still have fields that don’t join cleanly.

## Additional thought:
- Begin documenting data flow and field mappings between systems.

---

### Date:  
**Week 7**, 03/28/2025

### Number of hours:  
12 hours

###  Rose:
- Finalized and signed project proposal.
- Used Python to clean datasets, build custom columns, and generate visualizations.
- Created Google Colab notebooks for each visual exploration. For example: I created Uanalytics, Ajay created GradApp, Panneer created the GradSlate.

###  Bud:
- Build interactive visualizations in Tableau or Power BI.

###  Thorn:
- Need key/legend for several coded columns in UAccess Analytics.

## Additional thought:
- Consider making one dashboard per theme to reduce cognitive overload.

---

### Date:  
**Week 8**, 04/03/2025

### Number of hours:  
10 hours

###  Rose:
- Completed preliminary dashboard trials in Tableau and Power BI.
- Shared draft visualizations with the team and refined based on feedback.
- Installed VPN for UAccess Analytics.

###  Bud:
- Eager to consolidate dashboards by priority: demographics, programs, GPA, completion.

###  Thorn:
- Still comparing platform strengths; Power BI offers more flexibility, Tableau better visuals.

## Additional thought:
- Might test Python Streamlit dashboards later if needed for advanced ML integration.

---

### Date:  
**Week 9**, 04/11/2025

### Number of hours:  
10 hours

###  Rose:
- Completed data cleaning and selection for final dashboard.
- Synced dashboard visuals with priority questions from the admissions team.

###  Bud:
- Begin correlation analysis between variables like GPA, completion rate, and residency.

###  Thorn:
- Some dashboard limitations in Tableau when layering multiple filters.

## Additional thought:
- Consider writing a mini-report for stakeholders explaining visual story flow.

---

### Date:  
**Week 10**, 04/18/2025

### Number of hours:  
6–8 hours

###  Rose:
- Finalized the list of visual questions with Tavia after internal prioritization.
- Team reviewed all available visualizations and selected the most impactful.

###  Bud:
- Begin working on final visuals like confirming the questions and then making a draft on Tableau.

###  Thorn:
- Ethnicity and start-date columns still not aligned properly for filtering.

## Additional thought:
- Run exploratory correlation analysis to help build a feature importance model.

---

### Date:  
**Week 11**, 04/24/2025

### Number of hours:  
10–12 hours

###  Rose:
- Created Tableau dashboard for admissions funnel (Admitted → Enrolled).
- Added visualizations for residency, ethnicity, and application volume.
- Built the draft dashboard as still learning Tableau.

###  Bud:
- Integrate slicers into dashboard for dynamic exploration.

###  Thorn:
- Dashboard layout still being debated between Power BI and Tableau.

## Additional thought:
- Ensure all visuals tie clearly to stakeholder-approved questions.
