# Case-Study-2-How-Can-a-Wellness-Technology-Company-Play-It-Smart?
## Google Data Analytics Capstone 

### Introduction

Bellabeat is a high-tech company that manufactures health-focused smart products. Developed products that  informs and inspires women around the
world. Collecting data on activity, sleep, stress, and reproductive health has allowed Bellabeat to empower women with
knowledge about their own health and habits. Since it was founded in 2013, Bellabeat has grown rapidly and quickly
positioned itself as a tech-driven wellness company for women. Sršen (co-founder of Bellabeat) knows that an analysis of Bellabeat’s available consumer data would reveal more opportunities for growth. She has
asked the marketing analytics team to focus on a Bellabeat product and analyze smart device usage data in order to gain
insight into how people are already using their smart devices. Then, using this information, she would like high-level
recommendations for how these trends can inform Bellabeat marketing strategy.

### ASK

#### Stakeholders

1. Urška Sršen: Bellabeat’s cofounder and Chief Creative Officer
2. Sando Mur: Mathematician and Bellabeat’s cofounder; key member of the Bellabeat executive team
3. Bellabeat marketing analytics team: A team of data analysts responsible for collecting, analyzing, and
reporting data that helps guide Bellabeat’s marketing strategy.
#### Products

1. Bellabeat App: Pprovides users with health data related to their activity, sleep, stress,
menstrual cycle, and mindfulness habits. This data can help users better understand their current habits and
make healthy decisions. The Bellabeat app connects to their line of smart wellness products.
2. Leaf: Classic wellness tracker that can be worn as a bracelet, neckalce or clip. Tracks activity, sleep and stress.
3. Time: Combines the look of a watch with smart technology to track activity, sleep and stress.
4. Spring: Water bottle that tracks daily water intake using smart technology to make sure you are properly hydrated throughout the day.
5. Membership: Subscription based membership that gives 24/7 access to o fully personalized guidance on nutrition, activity, sleep, health and
beauty, and mindfulness based on their lifestyle and goals.

#### Business Task

The business task is to focus on a Bellabeat product and analyze smart device usage data in order to gain
insight into how people are already using their smart devices. Then, using this information, create high-level
recommendations for how these trends can inform Bellabeat marketing strategy.

#### Key Questions

* What are some trends in smart device usage?
* How could these trends apply to Bellabeat customers?
* How could these trends help influence Bellabeat marketing strategy?
* Are there any noticible gaps of usage that could be filled by marketing that feature? 
### PREPARE

#### Data Sources

FitBit Fitness Tracker Data which can be on [Kaggle]( https://www.kaggle.com/datasets/arashnic/fitbit) in 18 CSV files. The data set
contains personal fitness tracker from thirty fitbit users. Thirty eligible Fitbit users consented to the submission of
personal tracker data, including minute-level output for physical activity, heart rate, and sleep monitoring. It includes
information about daily activity, steps, and heart rate that can be used to explore users’ habits.

##### Data Limitations

* The sample size of the data set is small since it only uses data from 30 users
* The data set is from 2016 and currently it is 2023, which makes this data 7 years old.

### PROCESS

#### Picking data files

I picked `dailyActivity_merged.csv ` and  `sleepDay_merged.csv` files because they included a good summary of the data for both their intended categories of activity and sleep. I included `weightLogInfo_merged` because they weight is a large piece of health data as most people are trying to lower it. 

#### Applications Used
I used RStudio for my data cleaning, analysis and visualisations as the data sets were not too large and I could do all of them in one application easily. 

### ANALYZE

#### Import and Explore

All of the R code can be found with this [link] (https://github.com/brianchmiel1/Case-Study-2-How-Can-a-Wellness-Technology-Company-Play-It-Smart-/blob/main/r_script).

#### Summary Statistics

### SHARE

##### Data Visualizations



### ACT

* One of the big things that stuck out to me was that weight was only logged 67 times and only 26 of the time was that it was logged by a device and not manually. I believe that Bellabeat is missing a large market that they could get into. I would suggest that they introduce a smart scale that will automattically log the users weight and other measuraments into the Bellabeat app so that users could track that data more easily.
* 
