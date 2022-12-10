# Bellabeat_case_study
Google Data Analytics Capstone Project
This is a Bellabeat data analysis case study titled “How Can a Wellness Technology Company Play It Smart?” in Google’s eight-course Data Analytics Professional Certificate program.  

In this case study, I assumed the role of a junior data analyst of the marketing analytics team at Bellabeat, a high-tech manufacturer of health-focused products for women.  

Using tools such as BigQuery, Google Sheets, Kaggle Notebooks and Tableau, I conducted an analysis of Fitbit usage dataset generated on 2016. The data analysis was conducted in six phases :
> #### ASK  
> #### PREPARE  
> #### PROCESS  
> #### ANALYZE  
> #### SHARE  
> #### ACT
### About the company  

Urška Sršen and Sando Mur founded Bellabeat, a high-tech company that manufactures health-focused smart products.
Sršen used her background as an artist to develop beautifully designed technology that informs and inspires women around the world. Collecting data on activity, sleep, stress, and reproductive health has allowed Bellabeat to empower women with knowledge about their own health and habits. Since it was founded in 2013, Bellabeat has grown rapidly and quickly positioned itself as a tech-driven wellness company for women.  

By 2016, Bellabeat had opened offices around the world and launched multiple products. Bellabeat products became available through a growing number of online retailers in addition to their own e-commerce channel on their website.  

### Marketing Strategy
The company has invested in traditional advertising media, such as radio, out-of-home billboards, print, and television, but focuses on digital marketing extensively. Bellabeat invests year-round in Google Search, maintaining active Facebook and Instagram pages, and consistently engages consumers on Twitter. Additionally, Bellabeat runs video ads on Youtube and display ads on the Google Display Network to support campaigns around key marketing dates.  
  
### Objective
Sršen knows that an analysis of Bellabeat’s available consumer data would reveal more opportunities for growth. She has asked the marketing analytics team to focus on a Bellabeat product and analyze smart device usage data in order to gain insight into how people are already using their smart devices. Then, using this information, she would like high-level recommendations for how these trends can inform Bellabeat marketing strategy.
# **ASK**
#### BUSINESS TASK  

Focus on one of Bellabeat's products and analyze smart devices data  and gain insight intp how customers are using their smart devices and come up with a marketing strategy for the company and high level recommendations for Bellabeat’s marketing strategy. 
Stakeholders would be the company’s Chief Creative Officer and cofounder, the member of the executive team and cofounder , and the marketing analytics team.  

#### KEY STAKEHOLDERS  

* Urška Sršen: Bellabeat’s cofounder and Chief Creative Officer
* Sando Mur: Mathematician and Bellabeat’s cofounder; key member of the Bellabeat executive team
* Bellabeat marketing analytics team: A team of data analysts responsible for collecting, analyzing, and reporting data that helps guide Bellabeat’s marketing strategy. You joined this team six months ago and have been busy learning about Bellabeat’’s mission and business goals — as well as how you, as a junior data analyst,can help Bellabeat achieve them
# **PREPARE**
**FitBit Fitness Tracker Data** (CC0: Public Domain, dataset made available through Mobius): This Kaggle data set
contains personal fitness tracker from thirty fitbit users. Thirty eligible Fitbit users consented to the submission of
personal tracker data, including minute-level output for physical activity, heart rate, and sleep monitoring. It includes
information about daily activity, steps, and heart rate that can be used to explore users’ habits.

* The data is from 2016 and so is outdated.
* The data may not meet the ROCCC criteria for reliability,originality,comprehensive,current,cited
* The dataset has only  limited sample of about 30 participants, which may not be representative of the entire population
* The dataset is about the fitbit tracker data obtained from Kaggle and not the original author, in this case the bellabeat historic data throughout the years.
* It lacks other relevant information such as demographic data of the participants,and key details for analysis as the company is a bramd for women and data particular about women's health would have been a key area for analysis.  
* The data was collected in 2016 so it may reflect the current trends in usage of smart devicesnot cited or vetted.

The data contains a lot of csv data files, of which some are relevant, some redundant and some are not necessary for our area of interest. To find the required data, a lot of steps are done. 
There are evident null values, and datatype constraints where the hours are given as 12:00 hour format and merged as a timestamp as string. The number of rows are inconsistent to different files. The minutesWide and Narrow does not add to ease of understanding of the data.   
# **PREPARE**
**FitBit Fitness Tracker Data** (CC0: Public Domain, dataset made available through Mobius): This Kaggle data set
contains personal fitness tracker from thirty fitbit users. Thirty eligible Fitbit users consented to the submission of
personal tracker data, including minute-level output for physical activity, heart rate, and sleep monitoring. It includes
information about daily activity, steps, and heart rate that can be used to explore users’ habits.

* The data is from 2016 and so is outdated.
* The data may not meet the ROCCC criteria for reliability,originality,comprehensive,current,cited
* The dataset has only  limited sample of about 30 participants, which may not be representative of the entire population
* The dataset is about the fitbit tracker data obtained from Kaggle and not the original author, in this case the bellabeat historic data throughout the years.
* It lacks other relevant information such as demographic data of the participants,and key details for analysis as the company is a bramd for women and data particular about women's health would have been a key area for analysis.  
* The data was collected in 2016 so it may reflect the current trends in usage of smart devicesnot cited or vetted.

The data contains a lot of csv data files, of which some are relevant, some redundant and some are not necessary for our area of interest. To find the required data, a lot of steps are done. 
There are evident null values, and datatype constraints where the hours are given as 12:00 hour format and merged as a timestamp as string. The number of rows are inconsistent to different files. The minutesWide and Narrow does not add to ease of understanding of the data. 
