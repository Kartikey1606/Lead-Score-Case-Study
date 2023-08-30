# Lead-Scoring-Case-study
Lead scoring case study using Logistic Regression

An education company named X Education sells online courses to industry professionals. Many experts who are interested in the courses visit their website on any given day and search for courses. 

 
On several websites and search engines like Google, the firm advertises its courses. Upon arriving at the website, these visitors may explore the courses, submit a form for the course, or watch some videos. These persons are categorized as leads when they fill out a form with their phone number or email address. Additionally, the business receives leads from earlier recommendations. Once these leads are obtained, sales team members begin calling, sending emails, etc. 
Some leads are converted during this procedure, but most are not. **At X Education, the normal lead conversion rate is roughly 30%.** 

X Education currently has an extremely low lead conversion rate despite receiving a large number of leads. For instance, only approximately 30 of the 100 leads they could gather in a day might really be converted. The goal of the business is to find the most promising leads, commonly referred to as "Hot Leads," in order to increase the efficiency of this process. The lead conversion rate ought to increase if they are successful in finding this group of leads since the sales staff will now concentrate more on speaking with potential leads rather than calling everyone.


You have been asked by X Education to assist them in choosing the leads that have the best chance of becoming paying clients. The business wants you to create a model in which you give each lead a lead score such that leads with higher lead scores have a better probability of converting, while leads with lower lead scores have a lesser chance of converting.

**The goal lead conversion rate, according to the CEO in particular, is somewhere around 80%.**


The data set is provided as a compressed file with a data dictionary. The target variable in this instance is the column "Converted," which indicates whether a previous lead was converted or not. A value of 1 indicates that the lead was converted, while a value of 0 indicates that it was not. As good as a null value, the 'Select' level is present in many category variables and must be handled. 


**Objectives of the Case Study**

This case study has a number of objectives, including:

Create a logistic regression model to provide each lead a lead score between 0 and 100 that the business may use to target potential prospects. In contrast, a lower number would indicate that the lead is chilly and unlikely to convert, while a higher score would indicate that the lead is hot and most likely to convert.

