#### Business Fundamentals | Project Proposal

# Expanding Telemedicine to Offset Cost of Missed Appointments 

## Client
* Who is your client and how will that client benefit from exploring this question or building this model/system?
    * Midtown East Primary Care, a small, urban, primary care practice, with a majority of patients who are older and live with chronic health conditions.  
    * Patients have a hard time getting around alone on public transportation and miss appointments while the practice loses time and money. 
    * Unused 60-minute time-slots cost [$200 on average, costing the U.S. $150 billion](https://www.hcinnovationgroup.com/clinical-it/article/13008175/missed-appointments-cost-the-us-healthcare-system-150b-each-year) each year from missed appointments alone. 
    * Patients may [benefit from telehealth services](https://www.cdc.gov/dhdsp/pubs/telehealth.htm) when they can't make it to in person visits without interrupting their care. 
    * A patient who misses an appointment is [more likely to delay care](https://www.athenahealth.com/knowledge-hub/financial-performance/no-show-effect-even-one-missed-appointment-risks-retention), even for people living with chronic conditions. 
    * During the COVID-19 pandemic, Medicare temporarily [expanded coverage of telehealth services](https://www.medicare.gov/coverage/telehealth) to help people access care without needed to leave their homes and congregate in medical waiting rooms. 
    * There is an opportunity for [patients who adopted telehealth](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7772717/) during the pandemic to continue using it. 
## Question
* What is the question behind your analysis or model and what practical impact will your work have?
    * Would older patients be open to using telemedicine services? Would enough to invest in the technology? Does the investment offset the cost of no-shows for the small primary care practice?
* What data science opportunity and potential application do you see?
    * In 2020, telehealth Using telemedicine service use data from the Centers for Medicare and Medicaid in 2020, it could give us insight into the trends of telehealth. 
* What is the purpose of the EDA you will do and the data science model you will propose?
    * Understand the factors that encourage patients to use telemedicine. 
## Impact
* What impact are you trying to achieve? In other words, what will your work do for your client? 
    * Reduce cost of no-shows by investing in telemedicine infrastructure.
* What is your impact hypothesis? 
    * Investing in telemedicine will lower costs associated with no-shows and increase access to care for patients. 
## Data Description
* What dataset(s) do you plan to use, and how will you obtain the data? 
    * [2021 Medicare Current Beneficiary Survey COVID-19 Winter Supplement](https://www.cms.gov/Research-Statistics-Data-and-Systems/Downloadable-Public-Use-Files/MCBS-Public-Use-File) 
    * [Survey of a sample of people enrolled in Medicare in 2020 (n=11,107) ](https://www.cms.gov/files/document/2021mcbscovidpufdugwinter.pdf)
    * [Patient Characteristics Associated With Telemedicine Access for Primary and Specialty Ambulatory Care During the COVID-19 Pandemic](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7772717/)
* What is an individual sample/unit of analysis in this project?
    * One survey respondent randomly sampled from all Medicare beneficiaries. 
* What characteristics/features do you expect to work with?
    * The [features](https://www.cms.gov/files/document/covidpuf32021wtxt.txt) of interest are demographic and telehealth use:
        * age group
        * gender
        * race/ethnicity group
        * metro status
        * region
        * income group
        * language interview conducted
        * language spoken at home
        * internet access
        * computer, smartphone, tablet use
        * Zoom, Skype, FaceTime use
        * provider offers telehealth
        * type of telehealth offered
        * provider offered telehealth before pandemic
        * type of telehealth offered before pandemic
        * respondent had a telehealth visit before November 2020
        * type of telehealth visit respondent had before November 2020
        * respondent had a telehealth visit after November 2020
        * type of telehealth visit respondent had after November 2020   
    
## Solution Path 
* What is your data science solution path? 
    * Exploratory data analysis to see how many Medicare patients over the age of 75 in urban areas used telehealth services during 2021 to inform decision about investing in the technology. 
    * Classification model to identify what is the likelihood patients are interested in telehealth.  
    * Clustering for customer segmentation
* What other solution paths might be viable?  
    * Analyzing patient survey responses who are not enrolled in Medicare. 
* How else could you accomplish your goals if not through data science? 
    * Survey the current patient population about their interest in telehealth options if offered and learn more about the obstacles that lead patients to missing appointments. However, survey results can sometimes be misleading if respondents know how their answers will influence an outcome. For example, patients may say they are interested in telehealth because they know that the practice is looking to install one. This however, does not give us insight into their future behavior ??? where or not they would use it. 
## Criteria for Success
* What does success look like?
    * Less unused time slots
    * More patients with chronic conditions using telehealth
* How specifically will you measure your results in order to determine whether your work is successful?
    * 15% cost reduction from missed appointments
    * 10% increase appointment retainment 
    * 15% increase patient overall health due to continuity of care  

## Assumptions and Risks
* Given what you???ve said about your desired impact and the solution(s) you will use to achieve it, what are some assumptions you???re making? 
    * Patients are interested in telemedicine if offered. 
    * Patients may miss telehealth appointments. 
    * Patients have broadband access at home to attend telehealth video visits.
    * Physicians can assess patients via telemedicine as well as an in-person visit.
    * Physicians can request patients see them in person if they cannot assess their health well via telemedicine.
    * Patients still need to overcome challenges that contribute to missed appointments
* What are the risks to the approach you???ve identified?
    * The Medicare data or exploratory data analysis is biased or makes hidden assumptions about the patient population.
    * Investment in telehealth does not offset missed appointments. 
    * Data from Medicare population survey is not generalizable to one practice's patient population. 

## Tools
* How do you intend to meet the tools requirement of the project?
    * Excel, Tableau
* Are you planning in advance to need or use additional tools beyond those required?
    * None at this time.

## MVP Goal
* What would a minimum viable product (MVP)look like for this project?
    * Clear impact hypothesis and solution path. 
    * Visualizations comparing population of interest by income and age. 