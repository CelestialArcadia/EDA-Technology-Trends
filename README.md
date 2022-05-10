# EDA-Technology-Trends
Applications of various data analytics skills and techniques in data collection, data wrangling, exploratory data analysis, and creation of data visualization.

## Project Overview

* Executive Summary
* Introduction
* Methodology
* Results - 
    * Data Visualization & Dashboard
    * Discussion - Findings & Implications
* Conclusion
* Appendix

### I. Executive Summary

The first step in solving any data analysis problem is <b>Data Collection</b>. It can be done through various forms and sources. In this project, it will be collected through <b>Web Scraping</b> and <b>Web APIs</b>.

Sources including:
    * Surveys
    * Job Postings
    * Training portals

Data collected from the web is often if not, almost always raw and unclean. So, the data need to be prepared for the analysis.

Achieving this will be using <b>Data Wrangling Techniques</b>; which means that the data needs to be consistent, and without missing values and errors.

After finishing up with the data cleaning, next comes the application of statistical techniques to <b>analyze the data</b>, and identify insights and trends. Posing questions are important in order to find accurate solutions, and these questions are:
    * What are the top programming languages in demand?
    * What are the top database skills in demand?
    * What are the highest paying programming jobs?

Consequently, the findings will be put together through creating a <b>Data Visualization</b> utilizing the IBM Cognos Analystics to build an interactive dashboard.

Finally, the presention through storytelling using a written report or as a presentation.

### II. Introduction

A new hire as a Data Analyst by a global IT, and business consulting services firm, need to identify future skill requirements in order to keep pace with the constantly changing technologies and remain competitive.

The principle of the project is to answer one key question - <b> What are the current skill requirement in technology field</b>

After going through the whole process of analysing data, the result will inform the consulting firm of the key technical skills needed at the moment so the firm can focus on putting effort and resource into developing valuable technology assets. This is essential in the success of a business because, it's only possible to understand the market's needs through knowing the current trends, otherwise, the firm might slowly slide into obscurity, as well as it will cost tons of money if the firm works in the wrong direction.

As well as it may help new graduates or any person interested building a career based on the current industries' trends.

### III. Methodology

<b>Data sources and methods</b> implemented in this project are mentioned in the "project-eda-main" file.

### IV. Results - Data Visualization & Dashboard

After the data was cleaned, a dashboard was created on the IBM Cognos Analytics platform.
[Interactive-Dashboard](https://dataplatform.cloud.ibm.com/dashboards/af0fe02f-5a82-45d4-9467-e26384b25254/view/4332fc7722a062ca62f5b1e407cf7f047432745de1bb8a5286807b4906697197a86b1a96c82e1e5cd8450036a7ea12589c)

### IV. Results - Findings & Implications

Here are some charts showing comparisons of the technology trends:

<b> Programming Language Trends Comparison </b>

![Top 5 Programming Language in 2019](/graphs/top-5-programming-languages-2019.png)

Based on "Stack Overflow Developer Survey 2019

![Top 5 Programming Languages in 2020](/graphs/top-5-programming-languages-2020.png)

Based on "Stack Overflow Developer Survey 2019

Javascript and HTML/CSS remain in the top two regardless of 2019 or 2020, which implies that web development is still the highest in demand. Python jumps from the top five currently to the top three in the future which implies a rapid increase in the popularity of a general-purpose programming language that's easy to learn. SQL is floating around the top three in 2019 and the top four in 202 potentially, which suggests that although it’s not at the highest ranking, it still plays a significant role in the tech field. TypeScript is not on the top five in 2019 chart but making it to the number five in 2020 implies that it’s expected to be more popular in the future.

<b> Database Trends Comparison </b>

![Top 5 Databases in 2019](/graphs/top-5-database-2019.png)

Based on "Stack Overflow Developer Survey 2019

![Top 5 Databases in 2020](/graphs/top-5-database-2020.png)

MySQL is the most popular database in 2019 and still maintains in the top four in 2020. Microsoft SQL is the second most popular, however, it falls out of the top five list in 2020, losing its popularity to other databases. PostgreSQL is seemingly gaining popularity, jumping from the top three in 2019 to the top one in the year 2020. It will stay competitive for quite some time. MongoDB is making its way up as well, from the top five of the list and making it to the top two in 2020.

<b> Survey Respondent Demographic </b>
Below is a demographic dashboard that I developed based on the developer survey data. It showcases the gender, age, education level, and country of origin of the survey respondents.

![Survey Respondent Demographic](/graphs/Survey-Respondent-Demographic.png)

Based on "Stack Overflow Developer Survey 2019"

<b>Key information about the developers’ demographic:</b>

*   93.5% of the population are men, leaving only 6.5% women in the field. There is a huge gender gap in the technology workforce.

*   The map where it’s the darkest blue demonstrates that most of the population is heavily concentrated in the United States.

*   Respondent's age range is roughly in the 20s to 30s.

*   The education level lies mostly in the attainment of a  Bachelor's degree or a Master's degree.

From the demographic data analyzed, there are large gaps in the technology industry. More opportunities can be given to women and people in other geographic locations besides the United States. so the technology workforce would be more diversified.

### V. Conclusion

Based on programming languages' and databases' trends out there, and collerating it to the current technical skills needed for the firm. Python, Swift, and Javascript seem to be widely used in recent years. Python is known for its readability. It allows programmers to write clear and logical codes without complexity. Swift is purposed for developing mobile applications. Javascript is exceptionally flexible as it is used for both web frontend and backend applications. They all seemingly carry the characteristics of mobility, simplicity, and flexibility. The firm can certainly focus on investing more resources into these areas.

### VI. Appendix

While exploring the data, I also created a chart based on the top five most popular development environments that respondents picked. Visual Studio Code seems to be the most popular one that engineers use.

![Top 5 Development Environments](/graphs/top-5-dev-environment.png)
Based on "Stack Overflow Developer Survey 2019"
