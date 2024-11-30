# DSCI 100: Group 11 Project 
Authors: 
Ishita Sharma (66518101), Eric Haung, Yunfeng Bu(70556543), Andrew Liu

## Introduction ## 

The objective of this project is to understand user behaviour when playing video games such as MineCraft. By understanding how users interact with the game, researchers can make adjustments that better serve the user. With this information they can also work on strategies to improve recruitment and create better experiences for the user. This will in turn keep users subscribed to the game for longer. The University of British Columbia’s Computer Science research team is using MineCraft to collect real-world data from users playing the game. For this project, we will be working on answering which kinds of players are most likely to contribute a large amount of data. The goal is to develop a model that can identify which players are most likely to engage heavily with the MineCraft server 

We will be using two datasets for this project, which we will combine into one dataset. The first one is the Players dataset which provides the following information; name, gender, age, experience level, subscription status, hashed email of user, number of played hours, player ID, and an organization name. The second dataset is the Sessions dataset which provides the following information; the users hashed email, start and end time, and original start and end time. To answer our specific question we will be using a variable that includes the total played hours as a response variable. And then our explanatory variable will include gender, experience, age, subscription status, and played hours. We will be combining the dataset by using a common variable which is the Hashed Email. 

Question:  We would like to know which "kinds" of players are most likely to contribute a large amount of data so that we can target those players in our recruiting efforts.


