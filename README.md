# An Analysis of Kickstarter campaigns!
# Overview of Project: 
The purpose of this analysis was to help our friend Louise create more succesful Kickstarter campaigns for plays. She already had success with the Kickstarter for her play 'Fever' and now we can use our analyzed data of other similar Kickstarter campaigns to continue her success. 
# Analysis and Challenges
We used many different tools and formulas to analyze our data, and created graphs to help visualize our results. Firstly, we wanted to find out if the launch date of a Kickstarter had any impact on it being successful. We started by filtering our parent category to 'Theater'so that our data would be most relevant to Louise. Then we created a pivot chart organized with data from the month the theater Kickstarters were launched and the number of successful, failed, or canceled campaigns in those months. We then used our chart to create a line graph to help us easily visualize our data, as you can see below.
![Outcomes Based on Launch Date](https://user-images.githubusercontent.com/82848585/116466267-45f32980-a83c-11eb-9a78-a6402069e4ca.png)
Now that we knew what effects the month you launch your theater Kickstarter might have, we wanted to find out how important the financial goal of a campaign was to the outcome. We split our data up into 12 different goal categories from <1000 to >50000 then used the COUNTIFS function in EXCEL to filter for three ranges from our Kickstarter data: Outcome, Goal, and Subcategory. The COUNTIFS function allowed us to apply specific criteria to these ranges, succesful, failed or canceled for the outcome range, the 12 different goal categories, and the Subcategory 'plays'. After organizing a very specific data set that was most relevant to Louise, we created a line graph to help us better communicate our results to the client. 

# Results
![Parent Category Outcomes](https://user-images.githubusercontent.com/82848585/116466254-425fa280-a83c-11eb-8c0d-12c94f6bd2b0.png)
![Subcategory Outcomes](https://user-images.githubusercontent.com/82848585/116466260-44296600-a83c-11eb-9c49-b73fff51d257.png)
![Outcomes Based on Launch Date](https://user-images.githubusercontent.com/82848585/116466267-45f32980-a83c-11eb-9a78-a6402069e4ca.png)
