# [GenderData101](https://dataforsdgs.course.tc/catalog/gender-data-101-2)

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
* Dataset #2: [Here](https://docs.google.com/spreadsheets/d/15vNtkUuLm0F3m5kQK0j8RcaRqqRmIlGwNq-OBHH58i4/edit?usp=sharing)

#### Prompts
1. Summarize in a list the types of biases found in the datasets.

Dataset | Type of Bias | Explained
------------ | ------------- | ----------
#1 | Selection Bias | With respect to the "Race" category, "White" respondents are over represented in the dataset. Without any context on what community is being surveyed, I also think it is fair to say that "Black", "Asian", and "Other" racial groups are under represented. The survey results also do not appear to allow people to respond with multiple races. Given the history of settler colonialism, slavery, and war throughout much of the world, mutli-racial individuals/communities exist and should be represented in data.
#1 | Question Wording/Ordering Bias | With respect to the "Sex" category, there is no option for "Other" or "N/A" to represent lgbtqia+ respondents which may be using clinic services differently than "M" or "F" folks using clinic resources.
#2 | Social Desirability Response Bias | The question "Are you a legal resident?" has the ability to strike fear into the hearts of respondents and, more importantly, COVID-19 relief - the purpose of the survey - impacts citizens and non-citizens alike. This question may push respondents to respond "Yes" out of fear that "No" could make them targets while all they wanted to do was look for help in the midst of a pandemic.
#2 | Non-response bias | The question "Are you a legal resident?" has the ability to strike fear into the hearts of respondents and subsequently make them less likely to respond to the survey or less likely to answer certain questions on the survey (ex. some respondents did not respond to questions about their vaccination status).

2. Of the biases you found, which one(s) do you think are the most important to address first? Why?
> Of the biases I found, the most important one to address is the selection bias issue from dataset #1. 

3. What is one method or consideration that Dr. Lopez and/or Rumy can apply during data collection to prevent the biases you found?
> _Holding Text_

4. Are either of these datasets and example of gender data? Why or why not?
> _Holding Text_
