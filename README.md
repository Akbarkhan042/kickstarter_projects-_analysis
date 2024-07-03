# KICKSTATRER PROJECTS ANALYSIS (2009 - 2018)

## PROJECT OVERVIEW
Kickstarter is an American public benefit corporation based in Brooklyn, New York, that maintains a global crowdfunding platform focused on creativity.

The company's stated mission is to **"help bring creative projects to life"**. As of February 2023, Kickstarter has received US$7 billion in pledges from 21.7 million backers to fund 233,626 projects. The major categories of Kickstarter projects are  films, music, stage shows, comics, journalism, video games, board games, technology, publishing, and food-related projects.

People who back Kickstarter projects are offered tangible rewards or experiences in exchange for their pledges.

![R-removebg-preview](https://github.com/Akbarkhan042/kickstarter_projects-_analysis/assets/156647226/3c37d683-3a2b-4a12-96b9-2f7a7d58ac07)

## TABLE OF CONTENT
[PROJECT OBJECTIVE](#project-objective)

[PROJECT WORKFLOW](#project-workflow)

[DATA CLEANING](#data-cleaning)

[DATA TRANSFORMATION](#data-transformation)

[DATA ANALYSIS](#data-analysis)

[DATA VISUALIZATION](#data-visualization)

[DASHBOARD VIDEO SNIPPET](#dashboard-video-snippet)

[FINDINGS](#findings)



## PROJECT OBJECTIVE

The objective of this project is to analyse the dataset containing the records of all Kickstarter projects launched during the period of 2009 - 2018 to find out the trends in number of projects launched & amount pledged to these projects over the years. We would also like to uncover different patterns present in the dataset like which category had the most amount pledged, which country launched the most number of projects etc.

### DATASET
The dataset that we are working with contains records of all the Kickstarter projects launched around the world between the time period of 2009 to 2018.

The dataset consists of 374853 records & 11 columns.

### Tools
This project was completed in MS Excel only. From data import to data profiling, cleaning and transformation was all performed in Excel. Then after the dataset was analysed, visuals were created on the basis of those analysis and a dashboard was created with interactivity.

Different Excel tools that were utelised in this project:
- Power Query  : For data import, profiling, cleaning & transformation.
- Pivot Table  : For data summarization & aggregation and analysis.
- Pivot Chart  : For visualization.

## PROJECT WORKFLOW

The project workflow consisted of Data Import to Excel via the Power Query. Once the data was imported to power query the data was profiled for errors, nulls, empty records using various tool fror data profiling. Upon the completion of data profiling we proceeded to data cleaning and transformations.

## DATA CLEANING
This data comes from Maven Analytics & didn't required much cleaning. No blanks or nulls were present in the dataset, there were no textual errors like capitalization error or white spaces either.

## DATA TRANSFORMATION

Not much of data transformation was required in this project.
In order to properly perform the analysis I first of all extracted time from the Launch Date column as it was present in datetime format. Then I calculated the number of days the project ran for from Launch Date & End Date.

At last the Date from Add Column of Power Query was used to extract Year of launch, month name, month number from launch date. The month number was later used to sort the months properly via Power Pivot.

## DATA ANALYSIS

After the data cleaning and data transformation were complete we loaded the dataset to Pivot Table by **only creating connection** in order to summarize, aggregate and analyze our data.

We created different pivot tables to analyze different aspects of our dataset. We sorted and filtered the pivot tables too in order to arrange them in decending order and extract the top-10 values only.

Different questions that were answered:
- Month wise number of projects, backers & amount pledged over the years.
- Category wise number of projects, backers & amount pledged over the years.
- Project state was number of projects & amount pledged.
  
Different measures like total projects, total category of projects, total pledged $, Avg. goal per project etc were created from thr power pivot section of excel.

## DATA VISUALIZATION

When we were done with our required analysis we visualized the results of the pivot tables using the Pivot Charts.

- Simple charts like a combo chart having 2 field as an Area chart and Line chart was used to display the trent over time.
- Excel formula alongwith developer option is used to provide chart selection option.
- Bar charts was used to show the manufacturers with most recalls & potentially affected consumers and the most frequent cause for recall.
- A minimal design was chosen with very suttle colors in order to not make the dashboard busy.
- Popping colors was primarily used to guide viewer's attention to are of interest.

## **DASHBOARD VIDEO SNIPPET**

https://github.com/Akbarkhan042/kickstarter_projects-_analysis/assets/156647226/fd92dcfc-90fd-4e6d-9ad3-52adfe1ed382

## FINDINGS

Upon the completion of our data analysis we have the following findings.

- Over the years the number of projects veing launched on **Kickstarter** platform is having an upwards trend.
- Games, Design & Technology categories are thr top-3 by amount of **$** pledged.
- The top-3 ciuntries that launched projects on **Kickstarter** are The United States of America, The United Kingdom & Canada respectively.
- Film & Video, Music and Publishing are the top-3 categories in which most number of projects were launched.
