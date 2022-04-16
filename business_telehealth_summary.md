Business Fundamentals | Summary

# Expanding Telemedicine to Offset Cost of Missed Appointments 

## Abstract

[100 words]

## Design

**Business Opportunity**

The COVID-19 pandemic and Medicare's [temporary expansion of covered telehealth services](https://www.medicare.gov/coverage/telehealth) accelerated the adoption of patients meeting with their doctor via phone or video. While this was crucial during the pandemic to help people access care without needing to take public transportation and congregate in medical waiting rooms, it may have opened an opportunity for medical practices to avoid the costs associated with patients missing their medical appointments. Unused 60-minute time-slots cost medical practices `$` [200 on average](https://www.hcinnovationgroup.com/clinical-it/article/13008175/missed-appointments-cost-the-us-healthcare-system-150b-each-year), costing the U.S. `$` 150 billion each year from missed appointments alone.
There is an opportunity for [patients who adopted telehealth](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7772717/) during the pandemic to continue using it.


analysis of private claims data,
we estimate that over 20% of all
medical visits in the U.S. will be
conducted via telehealth this year,
representing $29 billion of medical services
in 2020.
Before the COVID-19 pandemic, only
14% of Americans had done
telemedicine at least once. The
number of patients with a chronic
condition was significantly higher, with
35% reporting that they had engaged
with their physician via telemedicine. 

28% of Americans reported they feel
telemedicine is the same or better quality
of care when compared to in-person
doctor visits, while 53% of those with a
chronic illness feel it is the same or better.

Physicians in Larger Metro Areas
& East Coast States Are Using
Telemedicine the Most

https://c8y.doxcdn.com/image/upload/v1/Press%20Blog/Research%20Reports/2020-state-telemedicine-report.pdf


**Solution Path**

First, exploratory data analysis to see how many Medicare patients over the age of 75 in metro areas used telehealth services during 2020 and 2021 to inform decisions about investing in telehealth technology.
**Second, a classification model to predict whether an applicant will drop out at some point in the process; Admissions team can pay extra attention to and take additional action on those students predicted as likely to drop out**
**Finally, an unsupervised clustering to better understand the types of Metis applicants and their respective drop-out rates; each cluster might warrant a different intervention**

**Impact Hypothesis** 

Offering telehealth services to patients would reduce costs the medical practice incurs due to no-shows.

**Measures of Success**
* 15% cost reduction from missed appointments
* 10% increase in appointment retainment
* 15% increase in patient overall health due to continuity of care 

**Risks**
* Telehealth services have hidden costs that do not offset the income lost to no-shows.
* Patients still need to overcome challenges that contribute to missed appointments if their doctor needs to see them in person
* The Medicare data does not represent the patient population of the client practice and is not generalizable.

**Assumptions**
* Patients ages 75+ are more likely to live with one or more chronic conditions that impede their ability to get around on public transportation.
* Patients are interested in telemedicine if offered and have reliable internet at home to access it.
* Physicians can assess patients via telemedicine as well as in-person visits.

## Data

The Medicare Current Beneficiary Survey (MCBS) is an ongoing survey of people enrolled in Medicare. The survey's goals are to collect information about access to care, satisfaction with care, and special topics. The data for this analysis (Winter 2021 survey) asked participants about access and use of telehealth services (video and audio), access to technology (internet at home, computers, smartphones, tablets), and use of video conferencing services (e.g., Zoom, Skype, FaceTime).

## Algorithms 

This analysis examines data from respondents (n=4305) in the U.S. Northeast and West. 
Summary of demographics (age, gender, race, income,) and their use of telemedicine since November 2020, and where they chose to forgo care during the COVID-19 pandemic and why (lack of transportation, to avoid risk of being in a medical facility, not feeling comfortable leaving their home). 

* EDA in Google Sheets
**Exploratory data analysis and visualization techniques are effectively used to clean, explore, aggregate, and visualize the data. Patterns and insights obtainable from the data are interpreted correctly. The analysis provides evidence that the proposed data science project is a feasible solution to the client problem.**

## Tools

* [Google Sheets](https://docs.google.com/spreadsheets/d/1D6C3ND8lyubF3_ExAL7TZzlsHO7_-m1A3CbWIuYEd6Q/edit?usp=sharing): data cleaning, pivot table analysis, prelimninary charts
* [Tableau](insert tableau link): data visualizations <br/>

## Communication

Slides and data are available at: https://github.com/slp22/business-project





