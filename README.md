# IBM-Data-Analyst-Capstone-Project
Peer-Graded Assignment: Building a dashboard with Cognos
Dashboard Embedded (CDE)
Estimated time needed: 45 minutes
In this assignment, you will create some visualizations and add them to dashboards using Cognos Dashboard Embedded (CDE).
Software Used in this Assignment
In this assignment you will use the free lite plan version of Cognos Dashboard Embedded (CDE) through IBM Cloud.
Dataset Used in this Assignment
The dataset you are going to use in this assignment comes from the following source: https://stackoverflow.blog/2019/04/09/the-2019-stack-overflowdeveloper-survey-results-are-in/ under a ODbL: Open Database License.
We are using a modified subset of that dataset for the assignment, so to follow the assigment instructions successfully, please use the dataset provided with
the assignment, rather than the dataset from the original source.

Guidelines for the Submission
1. Download the 2 files m5_survey_data_demographics.csv and m5_survey_data_technologies_normalised.csv. Upload these 2 CSV files as data
assets to your project in CDE.

2. Create 3 dashboards (3 separate tabs under a single dashboard) as follows:
One dashboard using the 2 x 2 rectangle areas tabbed template - rename this dashboard tab to Current Technology Usage.
One dashboard using the 2 x 2 rectangle areas tabbed template - rename this dashboard tab to Future Technology Trend.
One dashboard using the 2 x 2 rectangle areas tabbed template - rename this dashboard tab to Demographics.

3. On the Current Technology Usage dashboard tab, use the data asset m5_survey_data_technologies_normalised.csv and capture the following
metrics as visualizations:
![image](https://github.com/tnguy25/IBM-Data-Analyst-Capstone-Project/assets/125770693/c483f86b-15fb-45b8-85a6-07dff886d7b5)

In the first rectangle (Panel 1):
Capture Top 10 LanguageWorkedWith.
Visualize as a Bar chart.
Utilize Bars, Length, Color fields of Bar chart.
Include Show value labels feature.
Include a proper Chart title.
In the second rectangle (Panel 2):
Capture Top 10 DatabaseWorkedWith.
6/21/23, 2:00 PM about:blank
about:blank 2/4
Visualize as a Column chart.
Utilize Bars, Length, Color fields of Column chart.
Include Show value labels feature.
Include a proper Chart title.
In the third rectangle (Panel 3):
Capture PlatformWorkedWith.
Visualize as a Word cloud chart.
Utilize Words, Size, Color fields of Word cloud chart.
Include a proper Chart title.
In the fourth rectangle (Panel 4):
Capture Top 10 WebFrameWorkedWith.
Visualize as a Hierarchy bubble chart.
Utilize Bubbles, Size, Color fields of Hierarchy bubble chart.
Include a proper Chart title.
<img width="1193" alt="image" src="https://github.com/tnguy25/IBM-Data-Analyst-Capstone-Project/assets/125770693/73a73bdc-79eb-4a6a-9059-80f572390441">


5. On the Future Technology Trend dashboard tab, use the data asset m5_survey_data_technologies_normalised.csv and capture the following
metrics as visualizations:
In the first rectangle (Panel 1):
Capture Top 10 LanguageDesireNextYear.
Visualize as a Bar chart.
Utilize Bars, Length, Color fields of Bar chart.
Include Show value labels feature.
Include a proper Chart title.
In the second rectangle (Panel 2):
Capture Top 10 DatabaseDesireNextYear.
Visualize as a Column chart.
Utilize Bars, Length, Color fields of Column chart.
Include Show value labels feature.
Include a proper Chart title.
In the third rectangle (Panel 3):
capture PlatformDesireNextYear.
Visualize as a Tree map chart.
Utilize Area hierarchy, Size, Heat fields of Tree map chart.
Include Contrast label color feature.
Include a proper Chart title.
In the fourth rectangle (Panel 4):
Capture Top 10 WebFrameDesireNextYear.
Visualize as a Hierarchy bubble chart.
Utilize Bubbles, Size, Color fields of Hierarchy bubble chart.
Include a proper Chart title.
<img width="1213" alt="image" src="https://github.com/tnguy25/IBM-Data-Analyst-Capstone-Project/assets/125770693/26c083e7-2c32-40ed-a33c-afb82e563f66">

6. On the Demographics dashboard tab, use the data asset m5_survey_data_demographics.csv and capture the following metrics as visualizations:
Use Filters for this tab feature to filter out entries of other types except Man and Woman from the data point Gender.
In the first rectangle (Panel 1):
Capture Respondent classified by Gender.
Visualize as a Pie chart.
Utilize Segments, Size fields of Pie chart.
Include Dispay % feature.
Include a proper Chart title.
In the second rectangle (Panel 2):
Capture Respondent Count for Countries.
Visualize as a Map chart.
Utilize Regions-Locations, Regions-Location color fields of Map chart.
Include a proper Chart title.
In the third rectangle (Panel 3):
Capture Respondent Count by Age.
Visualize as a Line chart.
Utilize x-axis, y-axis fields of Line chart.
Include Show value labels feature.
Include Show markers feature.
Include a proper Chart title.
6/21/23, 2:00 PM about:blank
about:blank 3/4
In the fourth rectangle (Panel 4):
Capture Respondent Count by Gender, classified by Formal Education Level.
Visualize as a Stacked bar chart.
Utilize Bars, Length, Color fields of Stacked bar chart.
Include Show value labels feature.
Include a proper Chart title.
