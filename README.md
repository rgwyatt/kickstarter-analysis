# Kickstarting with Excel
	An Evaluation of Kickstarter Theater Campaign Success Rates 
	
## Overview of Project
	Louise is an independent showrunner/theatre enthusiast interested in getting her play Fever crowdfunded on a website called Kickstarter. Our job in this example is to assist her in achieving that goal by combing through data for useful information that can help ensure her crowdfunding success.

### Purpose
	This project was intended to glean whether or not the outcome of crowdfunded plays and projects (namely on Kickstarter) fared differently based on several factors. The ones evaluated in this exercise were primarily launch date (Month, Year) and funding goals (minimum benchmark for funding).

## Analysis and Challenges
	This analysis is to provide Louise with actionable information on when best to start and how to best structure her crowdfunding campaign for her play Fever.
### Analysis of Outcomes Based on Launch Date
	Launch Dates were looked at year over year, eliminating the presently live campaigns becaust they are incomplete instances of data. The trends, by month, suggested that both the total number of campaigns and the percentage of campaigns that turned successful were higher in the summer months. Alternatively, we see a dip in both campaigns run AND campaign success rate in the winter months, around the holidays when people's money is likely otherwise tied up.

### Analysis of Outcomes Based on Goals
	Goals were organized into tiers, the lowest being $1000 or less. The highest tier was $50,000 or greater. Each tier in between was split by increments of $5000. We have far more data from campaigns at the lower end of the spectrum, and they are far more likely to succeed than what we've seen from the higher goal tier campaigns.

### Challenges and Difficulties Encountered
	I didn't encounter many challenges or difficulties in this exercise, but I can imagine that a lack of familiarity with especially the COUNTIFS multiple argument function could present issue for newer, less-experienced Excel users.
	One thing I did have to learn was the implementation of the DATE function from Epoch time. That was at first confusing and confounding and resulted in data that looked different from the examples shown.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
	1. The best chance for a successful funding of your campaign is a launch date during the summer months, with a zenith in May.
	2. The worst chance for a successful funding of your campaign is a launch date during the winter months, with a nadir in November-December.
- What can you conclude about the Outcomes based on Goals?
	1. Crowdfunding campaigns with lower fundraising goals enjoyed the highest percentage of successful funding.
	2. We would certainly need a larger sample size or a sample size with a longer runtime to glean more reliable/siginificant data for campaigns with goals over $25,000.
- What are some limitations of this dataset?
	1. Sample size is a massive limiter, especially on the higher goal tiers.
	2. Kickstarter isn't the only crowdfunding website, and it isn't specialized to the category we're looking at evaluating. So our data is only from a single source/perspective. Having data from other sources in a similar vein might end up telling us Louise shouldn't be using Kickstarter at all.
	3. Crowdfunding sites like Kickstarter haven't been around all that long; KS was founded in 2009. A longer history of campaigns will normalize the dataset more.
- What are some other possible tables and/or graphs that we could create?
	1. I think the most obvious one is probably Outcomes based on Staff Pick and/or Spotlight or not. Marketing is an enormous part of these crowdfunding endeavors' chances at success, and these functions are essentially better marketing.
	2. One I'd personally be interested in is Outcomes based on Currency or Country. I don't think there is a large difference between the two categories themselves, but I can imagine a world where different populations' differing levels of engagement with theater in this way might influence where you'd want to focus future efforts, if not the present one.
