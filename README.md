# World-University-Ranking
This is an analysis to know the factors that influences international schooling.

*The picture is from the website of freepiks*
<p align="center">
  <img src="https://github.com/Amarabright/World-University-Ranking/blob/main/UNI2.avif" />
</p>

## Introduction
At some point in my life, I craved an international education. I went through various websites in order to make informed decision. I finally applied to several schools, got admissions but somehow  couldn't afford the fees, hence I didn't go. Don't feel bad, it's not uncommon :sweat_smile:

If you have funds and you are ready to make such an interesting move, then this project should help you. 
I belong to a community called ["She Code Africa"](https://shecodeafrica.org/), we decided to carry out some projects to show our skills and improve our learning. Amongst the listed projects, I chose this probably becasue of my previous expereience. 
So let's get down into it.

---
## Project Overview
It is alright to know different factors that can influence one's decision, the QS World University Rankings can be used to assist, give guidance and concentration on some particular measures before choosing a university.

In order for the UK to be able to evaluate the standing of its universities on a worldwide scale, the UK's finance ministry stressed the need for such ranking. A UK business by the name of Quacquarelli Symonds (QS) specializes in the analysis of universities all over the world. They acknowledged teaching, research, fostering employability, and internationalization as the four pillars of a university's mission. QS created its rankings to evaluate achievement in these areas.
The methodology it employs evaluates universities using six metrics:

1. Academic Reputation (40%)
2. Employer Reputation (10%)
3. Faculty/Student Ratio (20%)
4. Citations per faculty (20%)
5. International Faculty Ratio (5%)
6. International Student Ratio (5%)
More information about the methodology can be found [here](https://www.topuniversities.com/qs-world-university-rankings/methodology)

---
## Problem Statement
For this project, carry out an Exploratory Data Analysis to see what influences students to make their choices on a global scale.

---
## Skills and Concepts demonstrated:
1. Python (EDA for Data Analysis)
2. PowerBI concepts like:
 - creating columns for calculations for dates, time, and duration
 - Creating key performance indicators (KPIs) and other business calculations,
 - Developing general DAX calculations that deal with text and numbers,
 - Measures,
 - filters,
 - tooltips,
 - buttons and 
 - Data Visualization
 
### Aside carrying out this project on PowerBI. I also did an Exploratory Data Analysis using Python programming language. The script is also attached in this repository. You may want to check it out [here](https://github.com/Amarabright/World-University-Ranking/blob/main/World%20University%20Ranking.ipynb)
---

## Data Source:
Data is gotten from Kaggle, view it [here.](https://www.kaggle.com/datasets/padhmam/qs-world-university-rankings-2017-2022). The dataset has a total of 15 columns of data for 2017 - 2022.

It has the following attributes or fields labelled as "columns":

 - university - name of the university
 - year - year of ranking
 - rank_display - rank given to the university
 - score - score of the university based on the six key metrics mentioned above
 - link - link to the university profile page on QS website
 - country - country in which the university is located
 - city - city in which the university is located
 - region - continent in which the university is located
 - logo - link to the logo of the university
 - type - type of university (public or private)
 - research_output - quality of research at the university
 - student_faculty_ratio - number of students assigned to per faculty
 - international_students - number of international students enrolled at the university
 - size - size of the university in terms of area
 - faculty_count - number of faculty or academic staff at the university.
 
 ---
 ## Data Cleaning and Transformation
 Several cleaning processes were carried out like:
 - Removed rows that had empty values,
 - Trimmed some fields,
 - Transformed some texts
 - Removed 4 coulmns which are not useful to me (Link, Logo, Score and rank_display)
 
 ![](Uni1.png)           |         ![](uni6.png)
 
 This resulted to a clean data found below
 ![](Cleandata.png)
 
 ---
 
 ## Data Modelling
 The data is an Excel sheet which had all the columns and as such did not require modelling.
 
 ---
 ## Data Analysis and Visualization
 - Several Data Analysis Expression were created to enable me dig deep.
 - The insights were put into different visualization
 - It resulted to a report compriing of 3 pages:
    - -Univeristy Page
    - -Internatonal Students
    - -Research and Faculty-ratio
    
    
  The report can be interacted with on this [link](https://app.powerbi.com/view?r=eyJrIjoiYjE5YWI1ZDQtNDVjZS00ZGIxLWE5YTYtZjBkYzIwYWJhNTI2IiwidCI6IjM0ODhhMWU5LTQwNmYtNGMzNS04Yjc0LTkyOGUzNDM5Yzc1MCJ9)
   
  
  ## Features of the report.
  You can go through by clicking on the buttons on left bar, each button will take you to the page and you will see the visuals.
 
 The University Page
  ![](UniPage.png)
  
  
  The International Student's Page
  ![](UniIntstudents.jpg)
  
  
  The Research and Faculty-Ratio Page
  ![](UniResearch.jpg)
  
  ## Analysis and Insights
  
  1. There is a yearly trend in Universities, meaning that each year the number of Universities increases. 
  2. London is the city with the highest number of listed Universities followed by Seoul.  However, International students prefer USA as first study destination, UK as second and Australia as the 3rd country of choice.
  3. The students prefer Public Universities with Very High research output.
  4. There is a positive trend in the number of international students each year as the urge and preparations for study abroad increases per year.
  5. Student-faculty ratio is of great concern to the students as they prefer universities with lower ratio. They tend to believe that the lesser the ratio the more attention they would get from faculty members.
  6. Europe is the continent with the highest number of listed universities followed by Asia. In further drilling, US had the highest number of universities as choice for international education followed by UK.



 
