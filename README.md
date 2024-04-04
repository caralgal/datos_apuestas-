# Datos Apuestas
**Introduction:** This repository houses data on the registry of chances taken by Colombians in the South Pacific zone.  
the data is public and anonymous
## Programs Used
**python** 3.10 and newer
**MySQL Workbench 8.0 CE**
## Table of contents
<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [Planting of the problem](#Planting-of-the-problem)
- [Content](#Content)
  - [Data cleaning](#Data-cleaning)
  - [Data Manipulation](#Data-manipulation)
- [Data features](#Data-features)
- [Conclusions](#Conclusions)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Planting of the problem
Playing or taking chances is a random process, some people have their favorite numbers, others choose their numbers based on external factors. These second type of people tend to take a long time choosing and putting together their best numbers, this generates queues which translates into time that the customer must wait to make a chance or other operation, sometimes customers prefer to leave than wait.
optimize and provide a good service for these people and not generate congestion, agglomeration or abandonment of customers is the main thing.
what is proposed?
From patterns and characteristics of the person to create a program that can give recommendations of numbers that are likely to be liked by the customer. for this purpose having good quality data is essential.
# Content
This repository contains a database provided by the company Red de Servicios de Occidente S.A. of the Department of Chocó, with a date range from January 1 to January 31, 2024. 
## Data-cleaning
 It also contains a clean database to which different operations were performed in order to improve the quality of the information provided.
 empty values, duplicate values and also replace values that mean the same thing but were written in a different way. Finally, we visualized if there were outliers for the numerical variables and decided if they are necessary or can be eliminated.
## Data manipulation

# Data features
The file datos_apuestas_limpio.csv contains 23079 samples each describing 11 characteristics of the person to be analyzed, these 11 characteristics are:
- month (month in which the chance was played)           type(string)
- day (day in which the chance was played)               type(int64)
- dane (city in which the chance was played)             type(string) 
- type of game (modality in which the chance was played) type(string)
- name of the lottery (lottery bet by the client)        type(string)
- game modality (variations of the type of game)         type(string)
- number bet (3 or 4 digit number)                       type(string)
- age (customer's age)                                   type(int64)
- gender (client's gender)                               type(string)
- value wagered (amount of money wagered)                type(int64)
- jornada (if the chance was played in the morning, afternoon or evening) type(string)

# Conclusions
the data can be used for the final objective which would be to create an application that can recommend to a customer a number that is to his liking and thus optimize and provide a more complete service to the customer (bettor).
for the company it can be beneficial to implement new tactics to improve sales and improve customer service time.