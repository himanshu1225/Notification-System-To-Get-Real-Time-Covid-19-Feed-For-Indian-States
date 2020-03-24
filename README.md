Check out the blog of this project at the following link : 
https://medium.com/@Himanshu_bhati/notification-system-to-get-real-time-covid-19-feed-for-indian-states-1aa6a6a0f01a
# Introduction
Today we are going to understand how we can build a notification system for Covid-19, such that we will be able to know the number of active cases , recovered cases & deaths within India for any state. So basically, we will learn to build a notification system in which for every hour or half an hour or whatever the time you set, it will show a notification regarding the information as discussed above in real time update.
# Getting Started
Two questions come in mind when we think of this project:
* From where will we get the Data ? 
* How will we show the notification ?
# Data Source
Data is taken from Ministry of health and family welfare (https://www.mohfw.gov.in/). This is website of government of India. There we will find a table of Covid-19 State wise status.
# Notifications
We will use plyer  package to show the notifications. To install this package go to command prompt and type: pip3 install plyer
# Libraries and packages :
1. Notification : It is used to show notifications on the screen.
2. requests : It is used to get data from the website.
3. Beautiful soup : It is used to scrap the table data. 
4. time : It is used to process our notifications in time interval.
# Authors
* Himanshu Bhati - Complete Work
