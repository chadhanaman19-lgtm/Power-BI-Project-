
# Prism Insurance Pvt. Ltd. -Dashboard

A brief description of what this project does and who it's for

### Dashboard Link : https://vipst-my.sharepoint.com/:u:/g/personal/namanchadha_819_vipsedu_in/EaWIlETgwg5MrWy5_FKC7p4B0v1XqQ6by1JpX1GWZl2JDg?e=PBMK0K
(Download the file to view it)

## Problem Statement

This dashboard helps the Prism Insurance Pvt. Ltd. understand their customers better. It helps the them know if their customers are satisfied with their services. Through different ratings, they get to know their improvement area, & thus they can improve their services by identifying these areas. 

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a SQL file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so I need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present except column named "Arrival Delay". 
- Step 5 : In the report view, under the view tab, theme was selected.
- Step 6 : Since the data contains various fields, thus in order to represent them, card visuals were added showcasing sum of Premium Amount, Coverage Amount and Claim Amount. 
- Step 7 : Visual filters (Slicers) were added for 3 fields named "Policy Number", "Claim Number", "Customer ID".
- Step 8 : Two multi row card visuals were added to the canvas, representing total count of male and female customers.
- Step 9 : A bar chart was also added to the report design area representing the Premium Amount By Policy Type. 
- Step 10 : Line Chart Visual was used to represent Claim Amount by different age groups mentioned below,

  (a) Adult [Age<=60]

  (b) Elder [Age<=87]
  
  (c) Young Adult [Age<=24]

These age groups were created by adding a conditional column in Power query editor under Add column section.

- Step 11 : After that 3 more visuals were added 
  (a) A ribbon chart showcasing number of Claims by Claim Status Rejected, Settled and Pending. 
  (b) A donut chart showcasing the count of Active/Inactive Policies. For this a conditional column was added under the add column status.
"If Policy End Date is before or equal to 10-12-2024 then policy is Inactive else Active". 
  (c) A table visual for testing out the drill through feature by placing Policy Type under the visualizations pane.

  
<img width="1294" height="725" alt="Report Snapshot" src="https://github.com/user-attachments/assets/b17174cb-8ea5-4fc2-a105-5f8edd321437" />
