---
title: "Business Analysis and Integration"
collection: courses
permalink: /courses/data_analytics
excerpt: 'Business Analysis and Integration of Real TB Data Analysis at [Kwai](https://www.kuaishou.com)'
date: 2018-12-15
paperurl: 'http://charlesyan1.github.io/files/courses/Kwai.pdf'
citation: 'Jiawen Yan, Chenfei Song, Nianyao Xiao &quot; Why are You Unfollowed? Evidence from Short Video Platform Kwai&quot; <i>Complete but unpublished paper, 2018</i>'
---


Tasks: 
=====
In this 6 weeks course, we are expected to solve a real-world challenging problem. At Kwai, a leading short video platform in China, I, together with my other two talented team members, will explore the following two exciting questions:
1. Why do people unfollow others? 
2. Could we predict whether one will unfollow others? 
<br>

Data:
=====
Data is oil. To better solve those two questions, we have 4 "big" tables helping us. 
* Summary Table: 2.2 millions users' following behaviors on Sept. 1st and whether unfollowing on Sept. 30th; 
* Social Network Table: 0.37 trillion social network connections of users covered in summary table; 
* Behavior Table: 61 million short video upload and corresponding viewers' interactions data;
* User Information Table: registration information of users mentioned in Summary Table;

Analysis:
=====
Mark Zuckerberg once said: "all connections are good" and social media firms pay much cares about users connections. It would be invaluable if we could tell them what connections are good and what connections are bad, and how to strength good relationships and break bad ties. 
<br>
In this 6 week course, our team spent first four weeks cleaning data and analyzing trends, finding the channels through which users may untie; and the spent the last two weeks building prediction models and  improving prediction accuracy. 
<br>
During the data cleaning stage, we took the following steps:
* removing invalid and abnormal observations;
* merging the four tables into one "wide" table; 
* deriving new measurements evaluating their connections;
<br> 
To predict unfollow behaviors, we constructed a balanced dataset with 20,000 continuing following entries and 20,000 unfollowing entries for machine learning, keeping 80% as training set and 20% as testing set. Evidence from various machine learning algorithms such as Naive Bayes, Logistic Regression, Linear SVC, SGD, and neural network show that we could predict whether people's unfollowing behavior with accuracy over 75%. 
<br>
Feature of Importances derived by increased prediction accuracy show that social connections are vital to keep relationship long lasting: common followers and common fans are both most significant variables for major ML algorithms. 

![feature of importance](/images/courses/FI_2.png)
<br>

Main Findings and Implications: 
=====
* Part 1: Why do people follow/unfollow?
	* Various reasons could lead to follow/unfollow - product quality, connection strength, interaction frequencies etc.
	* Connection strength is one of the most important factor. To keep people connected, they need to have commonalities. 

* Part 2: Could we predict unfollow behaviors?
	* definitely YES!!!
	* Baseline logistic regression model could predict at 72% accuracy; 
	* By employing ensemble method, we could improve predict at accuracy by 3% to 75%; 

You may more details about this project by browsing our [final report](http://charlesyan1.github.io/files/courses/Kwai.pdf) and/or our [presentation slides](http://charlesyan1.github.io/files/courses/Kwai_PPT.pdf)

Recommended citation: Jiawen Yan, Chenfei Song, Nianyao Xiao &quot; Why are You Being Unfollowed? Evidence from Million of Observation from Kwai&quot; <i>Complete but unpublished, 2018</i>









