# Bellabeat - a case study
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
  
### Objective
Sršen knows that an analysis of Bellabeat’s available consumer data would reveal more opportunities for growth. She has asked the marketing analytics team to focus on a Bellabeat product and analyze smart device usage data in order to gain insight into how people are already using their smart devices. Then, using this information, she would like high-level recommendations for how these trends can inform Bellabeat marketing strategy.

**FitBit Fitness Tracker Data** (CC0: Public Domain, dataset made available through Mobius): This Kaggle data set
contains personal fitness tracker from thirty fitbit users. Thirty eligible Fitbit users consented to the submission of
personal tracker data, including minute-level output for physical activity, heart rate, and sleep monitoring. It includes
information about daily activity, steps, and heart rate that can be used to explore users’ habits.

The data contains a lot of csv data files, of which some are relevant, some redundant and some are not necessary for our area of interest. To find the required data, a lot of steps are done. 
There are evident null values, and datatype constraints where the hours are given as 12:00 hour format and merged as a timestamp but is a string. The number of rows are inconsistent in different files. The minutesWide and Narrow does not add to ease of understanding of the data.   

![Screenshot_20221210_141902](https://user-images.githubusercontent.com/83866928/206851691-248d612d-7632-4bc1-9de1-69cb66b09e09.png)
![Dashboard 1](https://user-images.githubusercontent.com/83866928/206861005-b75f397b-0ac9-43ad-b19a-652e24e76239.png)

![Dashboard 2](https://user-images.githubusercontent.com/83866928/206861008-2a707ed7-dc65-4624-88fe-0baa77a8b52b.png)
![Screenshot_20221210_142049](https://user-images.githubusercontent.com/83866928/207061655-aea0c0a8-3cd7-4060-b239-a53cf74f358d.png)


From this analysis,  
* The users tend to have a sedentary lifestyle, with peak activity days in mid-week compared to weekend. 
* The users enjoy fitness or calorie burning activities in the late evenings than mornings. This could be an insight for promoting activity during the other hours of the day to achieve overall fairly active lifestyle in addition to focusing on an intense fitness session at a specific part of day.
* The sleep schedule of the users are great, where we see calories burnt in early mornings. This could be a sign of good sleep. This is a basic assumption.  
* # **ACT**
I came to a few conclusions that could further improve and help towards Bellabeat's overall growth.  

From this analysis,  
* The users tend to have a sedentary lifestyle, with peak activity days in mid-week compared to weekend. Bellabeat could improve this by motivating light workouts or active hours on weekends. 
* The users enjoy fitness or calorie burning activities in the late evenings than mornings. This implies that other than an intense fitness session at a specific part of day, periodic notifications or nudges could remind the users to move about or stand to achieve overall fairly active lifestyle.

Bellabeat could have a reminder or track the hours without any activity and generate reports that users can go through. This could help them stay motivated.
Hourly standing or moving about can increase blood circulation and cause an end to continuous inactivity. 
Motivation like these can help overall lifestyle changes from sedentary to fairly active. 
A fairly active lifestyle can contribute to increased rest period during sleep hours and induce deep sleep.
This also include fitness activities outside the said weekdays. Bellabeat could notify the user to stay motivated even on weekends. 

