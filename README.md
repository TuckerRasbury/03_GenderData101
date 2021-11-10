# [GenderData101](https://dataforsdgs.course.tc/catalog/gender-data-101-2)

_For the purposes of this course Gender Data is defined as being "grounded in concepts and definitions that adequately reflect the diversity of women and men and capture all aspects of their lives."_

## Introduction 
Designed for gender advisors, data specialists, and other development professionals, Gender Data 101 Edition 2.0 is a 5-week blended online course featuring live events with gender and data experts that unpacks complex and practical considerations to understand, use, and share gender data with the ultimate goal of impact. Some of the exercises I complete(d) during the course will be available here for public viewing. The material will be organized by week and will reflect the activity I choose to complete (as oppose to all the rich available activies the course offers each week). 

My hope is that by creating this repository 1) others can benefit from some of the engaging questions asked in the course and 2) I can record my own journey as an intentional and progressive data professional. Thank you for visiting and please feel free to reach out if you have any questions.

### Course Objectives
1. Define best practices needed for gender data at all stages of the data life cycle: collection, processing, analysis, visualization, uptake, and impact.
2. Identify the multiple forms of systemic discrimination that affect the overall efficacy of gender data 
3. Evaluate the limitations of the gender binary and how it may affect the phases of the gender data lifecycle
4. Create action-oriented strategies and an intersectional approach to combat gender data inequities and biases

### Disclosure
The framing of the activites and objectives will be quotes or paraphrased, so much of the framework here is the intellectual mentorship/property/paradigm of the course leaders. The answers to the activities are my work.

## Week 1: Fundamentals of Gender and Data [October 13-16]
### Activity: Open Gender Data Scavenger Hunt
_Description: The goal of this activity is to explore a dataset with sex-disaggregated data and answer a few questions._

#### Summary Details

Dataset Title: Electronic Police Report 2018

Source: [Here](https://catalog.data.gov/dataset/electronic-police-report-2018)

Description: All Police Reports filed by New Orleans Police Department officers including incident and supplemental reports containing the item number, location, disposition, signal, charges, offender race, offender gender, offender age, victim age, victim gender, and victim race. Police Reports can be updated when subsequent information is determined as a result of an investigation. In order to protect the privacy of victims, addresses are shown at the block level.

Date Last Updated: November 12, 2020

#### Questions 
1. What are the gender options?: (Example Answer 1: Gender options are binary, only M/F, Example Answer 2: Gender options are Male, Female, Other, etc.)

> The gender options herein are Offender_Gender and Victim_Gender and are presented as a binary "MALE", "FEMALE", and blank fields without an option for "OTHER".

2. Does the dataset have quantitative or qualitative data? Or both?

> The dataset is primarily quantitative, but does contain some qualitative data (categorical data).

3. Does the dataset take an intersectional approach? If so, to what extent?

> The dataset does take an intersectional approach, but in a minimal way. The dataset contains some variables pertaining to RACE, ie. Offender_Race and Victim_Race, but these variables are not contextualized with any other quantitative (ex.average income in zipcode) or qualitative (ex. description of nuances in the dataset pertaining to these variables). 

4. Would you consider your dataset to be "gender data"? Why or why not?

> I would not consider the dataset to be "gender data". "Gender Data" for the purposes of this course is defined as being "grounded in concepts and definitions that adequately reflect the diversity of women and men and capture all aspects of their lives." The course definition goes further to state that "collection methods for gender data take into account stereotypes, social and cultural factors that may induce bias." With all of that said, the dataset has the variables denoting sex, but lacks the social and cultural factors that may allow bias in. Nowhere in the dataset is there any information about class or the rate of ["selective enforcement"](https://en.wikipedia.org/wiki/Selective_enforcement) officers choose to exercise, for example. Without any additional contextual information to nuance the dataset, I don't think the dataset crosses the threshold for "gender data".

5. Considering your answers to questions 2 and 3, what does the dataset do well and what is it missing? 

> The dataset contains gender variables which is a positive in the dataset and also has disaggregated data which is even better for analysis. The dataset is missing additional social or cultural (read: "intersectional") data, be that qualitative or quantitative.

6. What additional questions or comments you have for the dataset? For example: What methodologies were used to collect this data?

> I would have liked to see more information concerning the income/salary/wage/employment data for the area in which the arrest took place or for the people involved in the incident to get a better sense of the economic context the issue took place in. The dataset could also be nuanced by adding factors like number/rate of homelessness/vagrancy in a zipcode, sexuality of those involved in an incident, number of children of those involved, and/or marriage status.

## Week 2: Gender Data Collection and Processing [October 17-23]
### Activity: Spot the Biases
_Description: Review the datasets (2) and take note of any areas of the data that may suffer from biases using terms from the "Examining Bias lesson section. Address the prompts._

* Dataset #1: [Here](https://docs.google.com/spreadsheets/d/1AikInBFrKuBW9XmTS935RyzRIiDfJdwJgRw5yTQTNZs/edit?usp=sharing)
  * Description: A local clinic's database system shut down. A clinic employee decided to gather data via Google Sheets instead of the usual secure system. This dataset was shared via email within clinic.
  * Hypothetical Data Collector: Dr.Lopez
* Dataset #2: [Here](https://docs.google.com/spreadsheets/d/15vNtkUuLm0F3m5kQK0j8RcaRqqRmIlGwNq-OBHH58i4/edit?usp=sharing)
  * Description: A COVID-19 relief survey was sent via online link to households in a community in Chile. The link was sent during the weekend starting Friday at 5pm, to be completed by Monday. 142 households responded out 843 households surveyed.
  * Hypothetical Data Collector: Rumy

#### Prompts
1. Summarize in a list the types of biases found in the datasets.

Dataset | Type of Bias | Explained
------------ | ------------- | ----------
#1 | Selection Bias | With respect to the "Race" category, "White" respondents are over represented in the dataset. Without any context on what community is being surveyed, I also think it is fair to say that "Black", "Asian", and "Other" racial groups are under represented. The survey results also do not appear to allow people to respond with multiple races. Given the history of settler colonialism, slavery, and war throughout much of the world, mutli-racial individuals/communities exist and should be represented in data.
#1 | Question Wording/Ordering Bias | With respect to the "Sex" category, there is no option for "Other" or "N/A" to represent lgbtqia+ respondents which may be using clinic services differently than "M" or "F" folks using clinic resources.
#2 | Social Desirability Response Bias | The question "Are you a legal resident?" has the ability to strike fear into the hearts of respondents and, more importantly, COVID-19 relief - the purpose of the survey - impacts citizens and non-citizens alike. This question may push respondents to respond "Yes" out of fear that "No" could make them targets while all they wanted to do was look for help in the midst of a pandemic.
#2 | Non-response bias | The question "Are you a legal resident?" has the ability to strike fear into the hearts of respondents and subsequently make them less likely to respond to the survey or less likely to answer certain questions on the survey (ex. some respondents did not respond to questions about their vaccination status). The question is the first one listed so it comes off as very important and is followed by address. This information in the wrong hands could result in unintended arrests, deportations, family seperation, and/or imprisonment.

2. Of the biases you found, which one(s) do you think are the most important to address first? Why?
> Of the biases I found, the most important one to address is the selection bias issue from dataset #1. The bias in the dataset for "White" respondents could lead to erroneous strategy setting that does not represent the breadth of who uses, needs, or uses services up to certain price points. This bias is only made worse by the fact that sexual orientation is all together left out of the list of survey questions. 
> 
> My concern is that the pattern of services used might be different between racial groups and/or subsects of different racial groups (ex. black men compared to black women, or hispanic lgbtqia+ compared to the broader lgbtqia+ community). By addressing this bias in the dataset, the local clinic in the hypothetical scenario might be able to better assist their community, find that their resources could be directed more towards the type of people actually coming, or that respondents tend to stop seeking care after a certain point.

3. What is one method of consideration that Dr. Lopez and/or Rumy can apply during data collection to prevent the biases you found?

Dataset | Type of Bias | How to Prevent
------------ | ------------- | ----------
#1 | Selection Bias | The demographics of the communities served by the clinic and the demographics of the community at large need to be compared to the population that responded. Subsequently, if doing additional surveys are out of the question, one or more groups can be weighted so that they are represented more accurately for who uses services or could use their services. If additional surveys are possible, more surveys could be done with a new strategy on how to get underrepresented racial groups in the survey (ex. survey in additional languages or conducted live at strategic locations).
#1 | Question Wording/Ordering Bias | Replace with "Gender" and provide option for each of the following or an umbrella category for "Transgender", "Nonbinary", and/or "Prefer not to answer".
#2 | Social Desirability Response Bias | Remove the question about citizenship as it is not essential to the study or move it to later on in the survey after more important questions, COVID-19 related ones, have been answered to avoid bias.
#2 | Non-response Bias | Remove the question about citizenship as it is not essential to the study or move it to later on in the survey after more important questions, COVID-19 related ones, have been answered to avoid bias.

4. Are either of these datasets and example of gender data? Why or why not?
> Unfortunately, I do not think either dataset #1 or #2 qualifies as gender data. For dataset #1, while it contains sex disaggregated data it does not contain gender disaggregated data. For dataset #2, the dataset does not collect sex or gender data let alone get into the nuances/context of the lives of people of different genders. 
> 
> On a broader note, I think I am beginning to wonder what Gender Data might actually look like, aside from having a gender variable in a dataset. I'd like to see an example.


## Week 3: Gender Data Analysis [October 24- 30th]
### Activity: Next steps in COVID-19 gender data analysis
_Description: Review and assess data from hypothetical COVID-19 related research projects(s). Subsequently, answer questions about the data, the process, and what way their analysis could be made better by adding a gender data analysis framework to it._

#### Dr. Lopez's Research Questions
Dataset: [The Sex, Gender and COVID-19 Project](https://globalhealth5050.org/the-sex-gender-and-covid-19-project/)

Description: The COVID-19 Sex-Disaggregated Data Tracker is the world’s largest database of sex-disaggregated data on COVID-19. Dr. Lopez is primarily concerned with her own city's (Washington, D.C.) COVID-19 data. She has aggregated data from local nursing homes, hospitals, and clinics to analyze. We will help answer some of the questions the good doctor has about the data.

#### Questions
1. Describe the metadata of this dataset (Where is the data sourced? If there are multiple sources, list just a few)
> According to the course _"Metadata includes general information about the dataset(s). It often includes definitions, rationale, methodology descriptions, and information about outliers."_ The Sex, Gender, and Covid-19 project has:
> * status of sex disaggregated data broken down by country, 
> * status of covid-19 reporting by country, 
> * global level statistics on Covid-19 cases disaggregated by sex, 
> * and analyses of how sex and gender may or may not be included in policy directives around the world.
> 
> In summary, the project is an incredibly robust endeavor to collect, synthesize, and analyze sex disaggregated data from all around the globe. They also go on to use all of the data they have collected to push for more contries to collect and publicly report sex disaggregated data.
> 
> The sources used to produce this project include the following:
> * [Global Health 50/50](https://globalhealth5050.org) - is an independent, evidence-driven initiative to advance action and accountability for gender equality in global health.
> * the [African Population and Health Research Center](https://aphrc.org) - Is the continent’s premier progressive research institution and think tank, generating evidence to drive policy action to improve the health and wellbeing of African people. They focus on research, research capacity strengthening, and polcity engagement and communications.
> * and the [International Center for Research on Women](https://www.icrw.org) - ICRW is a global research institute whose research evidence identifies women’s contributions as well as the obstacles that prevent them from being economically strong and able to fully participate in society. ICRW translates these insights into a path of action that honors women’s human rights, ensures gender equality and creates the conditions in which all women can thrive. 
>
> The project goes a step further by enabling its audience to review and [download the data](https://globalhealth5050.org/the-sex-gender-and-covid-19-project/dataset/) at the global level, country, and variable level.

2. What specific data category should Dr. Lopez focus on and why? (For example: Men in Thailand and their COVID-19 death rate)
> Dr. Lopez should focus on Washington, DC level/local level Covid-19 reporting that covers the lifecycle of covid from infection to mortality. The project only appears to have country level statistics and since her work is locally focused she may need a new data source all together.

3. In what ways could a Gender Data Analysis Framework (GAF) help Dr. Lopez's analysis?
> A GAF with the current data available in the project might not be as helpful to Dr.Lopez since it does not dig enough into her region of interest. However, even at this stage, a GAF may identify impediments to resources being distributed (ie. medical information and care) to women globally that she can later connect to the situation of women in Washington, D.C. when she does data particular to her area of interest.
> 
> In particular I think the [Jhpiego's Gender Analysis Framework for Health Systems](https://gender.jhpiego.org/analysistoolkit/seven-steps-to-a-gender-analysis/) may be really useful. In the U.S. different communities have different beliefs about healthcare at large and COVID-19 in particular, so there may be a really meaningful correlation between what women in a community believe and how the rest of the community is performing COVID wise, acting as something of a bellweather for how the community may or may not respond to different vaccination drives or, dare I say, anti-vaccination drives.


## Week 4: Gender Data Visualization [October 31-November 6]



## Week 5: Gender Data Uptake and Impact [November 7-13]


## Dictionary
_Terms and videos listed herein are from the TechChange Gender Data 101 course and are reproduced here to add to this record of what I learned during the course._

### Week 2 Resources

#### Dictionary
* **Collection** is the process of gathering and measuring information in a systematic fashion.
* **Biases** are personal and/or systematic judgments and pre-conceptions.
* **Selection Bias**, also known as sampling bias, is choosing a sample that is not representative of the population being studied. Selection bias also results when participants not being randomly sampled to a condition.
* **Response Bias** is a general term for any external factor that can influence a respondent’s answers. 
* **Non-response bias** means certain members of the population being studied do not participate in the data capture. There are many reasons for non-responses bias. Examples include the medium of study (e.g. online survey) or time study is conducted (e.g. morning times).
* **Demand characteristics** are the ways participants of a study can influence the outcome. 
* **Social Desirability Response Bias** is a type of response bias is when a respondent is influenced to provide answers that are socially desirable and are not necessarily their true responses.
* **Question Wording/Ordering Bias** occurs if the question is worded or ordered in such a way that it favors one response over another.
* **Outlier/Extreme Response Bias** occurs when there are extreme data values. 
* **Processing** is the series of operations needed to prepare data for analysis.
* **Raw data** (also called dirty or unclean data) is data directly from the source. 
* **Incomplete data** is data that lacks the key information.
* **Duplicate data** is data that repeats itself.
* **Inaccurate data** is information that is not correct.
* **Inconsistent data** is unstandardized data.
* **Clean data** is data that is accurate and formatted to a set of rules. These rules can be determined by your organization or by your data analysis needs. Data cleaning helps edit or remove incomplete, duplicate, incorrect, and inconsistent data.
* **Data aggregation** is systematically combining data from multiple sources together. Processing may or may not involve aggregation.
* **Data security** is the commitment to confidentiality and integrity of data.
* **Personally Identifiable Information** also known as PII is any data that can be used to distinguish or trace an individual's identity.
* **Data encryption** is the process of converting data into code to prevent unauthorized access.

### Week 3 Resources

#### Video
* [_Intersectional Pay Equity_](https://www.youtube.com/watch?v=sMBhJHELb8s&t=582s) by WeAllCount - Intersectional analysis demonstrated with Pay Equity example

#### Dictionary
* **Metadata** is information about the data. This information includes general information about the dataset(s). It often includes definitions, rationale, methodology descriptions, and information about outliers. Metadata usually appears in footnotes or near the dataset description.
* **Ratio** compares the frequency of one value for a variable with another value of the same variable.
* **Rate** a measurement of one value for a variable in relation to another measured quantity.
* **Proportion** number of times a particular value for a variable has been observed, by the total number of values in the population.
* **Percentage** expresses a value for a variable in relation to a whole population as a fraction of one hundred.
* **Percentage Points** used to express increments, drops, or differences. It represents decimal points. These are different from percentages.
* **Mean** the arithmetic average of a set of numbers or distribution. It is the most commonly used central tendency of a set of numbers. It is used for normal distributions and it is not robust, as it is influenced by outliers.
* **Median** the numeric value separating the higher half of a sample, a population, or a probability distribution, from the lower half. It is used for skewed distributions. It is computed by listing all numbers in ascending order and locating the number in the center of the distribution.
* **Gender Analysis Frameworks** or (GAFs) are a collection of tools for gender analysis.
  * [Jhpiego's Gender Analysis Framework for Health Systems](https://gender.jhpiego.org/analysistoolkit/seven-steps-to-a-gender-analysis/) - Jhiepgo's GAF categorizes the lives of women and men, girls and boys, into four main domains. All domains intersect with power. The four domains: access to assets, beliefs and perceptions, practices and participation, institutions, laws, and policies
  * [Oxfam's Feminist monitoring, evaluation, accountability and learning (MEAL)](https://www.oxfam.ca/measuring-change-with-a-feminist-lens/) - Feminist Monitoring, Evaluation, Accountability and Learning (MEAL) is based on the understanding that transformative change in unequal gender and power relations is complex and non-linear. It challenges us to think differently about what is considered evidence, pushes the boundaries of how evidence is captured, questions who gives knowledge meaning and power, and promotes social transformation.
  * [Gender at Work Framework](https://genderatwork.org/analytical-framework/) - Gender at Work Framework can be used by change agents to uncover opportunities and barriers to gender equality, map strategy for change, and guide evaluations of progress. The top two quadrants are related to the individual. The right quadrants are changes in individual conditions and the left is individual consciousness and capability. The bottom two quadrants are related to the system.
  * [Harvard Analytical Framework](https://en.wikipedia.org/wiki/Harvard_Analytical_Framework) - The Harvard Analytical Framework, also known as the Gender Roles Framework, aims to identify the type and amount of work that men and women do in a household or community. The framework has three parts of inquiry: 1) Activity: Who does what? When? Where? 2) Access and Control: Who has access to what? Who has control over what? 3) Influencing Factors: What influences the division of labor and the access and control?

### Week 4 Resources

#### Video
* [Tufte's Rules for Graphical Integrity](https://youtu.be/RK0TSg6BU5s)
* [Policy Visualization Cheat Sheet](https://d2jbbv3z6z1uwh.cloudfront.net/course.tc/311-8/content/uploads/2019/11/14045721/PolicyViz-DataViz-Cheatsheet.pdf)
* [Junk Charts Trifecta](http://junkcharts.typepad.com/junk_charts/junk-charts-trifecta-checkup-the-definitive-guide.html)

#### Dictionary
* **Data visualization** the graphic representation of data.
* **Gender data visualization** the graphic representation of gender data.
* **Data Viz Framework** ask yourself the following questions as you visualize data:
  * Who is your viewer?
  * What types of decisions does your viewer make? What information do they need? How will your data visualization add value?
  * What is your viewer’s digital literacy?
  * What is your viewer’s prior experience with data visualization?
* **Tufte's Rules** for data visualization, consider " analyz[ing] the datasets you have, first. Discover the story that it tells before you choose a visualization platform, which runs the risk of pre-specifying certain narratives of the data." Here are the ten rules Tufte outlines:
  1. Show Your Data
  2. Use Graphics
  3. Avoid Chartjunk
  4. Utilize Data-ink
  5. Use Labels
  6. Utilize Micro/Macro
  7. Separate Layers
  8. Use Multiples
  9. Utilize Color
  10. Understand Narrative 
* **Schwabish's Core Principles** Jonathan Schwabish is a senior fellow at the Income and Benefits Policy Center at the Urban Institute. As an economist, he also specializes in data visualization and presentation design as a member of the communications team. He also hosts the PolicyViz Podcast, which focuses on data, open data, and data visualization.
  1. Show the data - The data is the most important part of the graph and should be presented in the clearest way possible. But that does not mean that all of the data must be shown—indeed, many graphs show too much. 
  2. Reduce the clutter - Chart clutter, those unnecessary or distracting visual elements, tend to reduce effectiveness.
  3. Integrate the text and the graph - Visualizations should be constructed to complement the text and, at the same time, contain enough information to stand alone.
  4. Preattentive Processing - Effective data visualization taps into the brain’s preattentive visual processing.
* **Junk Charts Trifecta** The Junk Charts Trifecta Checkup is a general framework for data visualization criticism. It serves to organize the thinking behind data viz pieces by addressing three points of investigation:
  1. What is the QUESTION?
  2. What does the DATA say? 
  3. What does the VISUAL say? 
* **Data Viz/ Visualization Tools** 
  * Excel - Excel makes it super easy to store, analyze, clean, and quickly visualize data.
  * [Piktochart](https://piktochart.com/) - A platform that generates beautiful, intuitive, and clean visuals for your data.
  * [Infogram](https://infogram.com/) - A web-based data visualization and infographics platform.
  * Canva - A simplified graphic design tool and website that allows those of us without much design sense to pass as graphic artists. 
  * [kepler.gl](kepler.gl) - high-performance web-based application for visual exploration of large-scale geolocation data sets. Built on top of deck.gl, kepler.gl can render millions of points representing thousands of trips and perform spatial aggregations on the fly.
  * [CARTO](https://carto.com/) - cloud computing platform that provides GIS, web mapping, and spatial data science tools. The company is positioned as a location intelligence platform due to tools with an aptitude for data analysis and visualization that do not require previous GIS or development experience.
