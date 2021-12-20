# Kickstarting with Excel

## Overview of Project

	This project is an analysis of Kickstarter campaign data for up-and-coming playwright Louise. We use Microsoft Excel for the transformation, sorting, filtering, and analysis of the data. The data spans years from 2009 to 2017, and includes campaign goals, pledge amounts, and the result of the campaign.

### Purpose
	
	Louise is looking to crowdfund her latest play *Fever* through Kickstarter. She estimates the play will cost apporximately $12,000 to produce. Because there are so many variables that could affect the success of a crowdfunding campaign she is looking to us to help her create a campaign with the best possible chance of success. We will filter the data to look at the outcomes of similar campaigns and find out what variables affect the success of a campaign the most. After analysis of the data we will be able to advise Louise on what she can do to ensure she has the best possible chance of making sure her play is fully funded. 

## Analysis and Challenges

	Before we could start the analysis we needed to make sure the data was in a format that we could easily analyze. The deadline and launch dates were given as UNIX timestamps and needed to be converted to a human readable format by using the formula `=(((<cell>/60)/60)/24) + DATE(1970,1,1)`. This formula converts the UNIX timestamp to hours and adds it to January 1st, 1970 in order to get the readable date.
	The column 'Category and Subcategory' was split into two separate 'Parent Category' and 'Subcategory' columns in order to allow more granular filtering of the campaigns. In addition we added a columns for the year the campaign started and the percentage of the funding goal the campaign received. However we did not use those columns in our final analysis. 

### Analysis of Outcomes Based on Launch Date

### Analysis of Outcomes Based on Goals

### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
