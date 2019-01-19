---
title: "Business Analysis and Integration"
collection: courses
permalink: /courses/data_analytics
excerpt: 'Business Analysis and Integration of Real TB Data Analysis at [Kwai](https://www.kuaishou.com)'
date: 2018-12-15
paperurl: 'http://charlesyan1.github.io/files/courses/Kwai.pdf'
citation: 'Jiawen Yan, Chenfei Song, Nianyao Xiao &quot; Why are You Unfollowed? Evidence from Million of Observations from Short Video Platform Kwai&quot; <i>Complete but unpublished paper, 2018</i>'
---


Tasks: 
=====
In this 6 weeks course, we are expected to participate in and to solve a real-world business problem faced by firms. In cooperation with Kwai, a leading short video platform in China, I, together with my other talented team members, will explore:
1. Why do people unfollow others? 
2. Could we predict whether one will unfollow others? 
<br>

Data:
=====
Data is modern oil. To better solve those two questions, we have 4 "big" tables helping us. 
* Summary Table: 2.2 millions users' following behaviors on Sept. 1st and whether unfollowing on Sept. 30th; 
* Social Network Table: 0.37 trillion social network connections of users covered in summary table; 
* Behavior Table: 61 million short video upload and corresponding viewers' interactions data;
* User Information Table: registration information of users mentioned in Summary Table;

Analysis:
=====
Like Mark from Facebook said: "all connections are good", social media firms care about users connections. It would be invaluable if we could tell them what connections are good and what connections are bad, and how could me strength good relationships and break bad ties. 
<br>
We spent first four weeks cleaning data and analyzing trends, finding the channels through which users may untie; and the last two weeks building prediction models, trying to improve prediction accuracy. 
<br>
During the data cleaning stage, we did three things:
	* removed invalid and abnormal observations;
	* joined the four tables into one "wide" table according to userid; 
	* derived new variables evaluating their connections;
<br>
This "wide" table give us plenty of rooms to do univariate trend analysis. This is pivotal as there are over 300 variables in this dataset. It's easy to get lost with so many variables. 

<br> 
To predict unfollow behaviors, we constructed a balanced dataset with 20,000 continuing following entries and 20,000 unfollowing entries for machine learning. Evidence from various machine learning algorithms such as Naive Bayes, Logistic Regression, Linear SVC, SGD, and neural network show that we could predict whether people's unfollowing behavior with accuracy over 75%. 
<br>
Feature of Importances derived by increased prediction accuracy show that social connections are vital to keep relationship long lasting: common followers and common fans are both most significant variables for major ML algorithms. 

![feature of importance](/images/courses/FI_2.png)
<br>

Main Findings and Implications: 
=====
* Part 1: Why do people follow/unfollow?
	* Various reasons could lead to follow/unfollow - product quality, connection strength, interaction frequencies etc.
	* Connection strength is one of the most important factor. 

* Part 2: Could we predict unfollow behaviors?
	* definitely YES!!!
	* Baseline logistic regression model could predict at 72% accuracy; 
	* By employing ensemble method, we could improve predict at accuracy by 3% to 75%; 

You may more details about this project by browsing our [final report](http://charlesyan1.github.io/files/courses/Kwai.pdf) and/or our [presentation slides](http://charlesyan1.github.io/files/courses/Kwai_PPT.pdf)

Recommended citation: Jiawen Yan, Chenfei Song, Nianyao Xiao &quot; Why are You Being Unfollowed? Evidence from Million of Observation from Kwai&quot; <i>Complete but unpublished, 2018</i>









