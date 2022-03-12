# Kickstarting with Excel

https://github.com/Azykan/kickstarter-analysis/blob/main/Kickstarter_Challenge.zip

## Overview of Project
To analyze the outcome of different campaigns based on their launch dates and their funding goals. 

### Purpose
To show Louise how other campaigns did per their launch dates and funding goals compared to her play "Fever".
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
First I filtered by "Theater". 
Then I Extracted the year from the launch date.
I then created a pivot table and a line chart showing failed, canceled, and successful campaigns by month.

https://github.com/Azykan/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png

### Analysis of Outcomes Based on Goals
First I filtered for "Plays".
Then I bucketed the goal values into 12 sections.
I used the total count of plays in each bucket to get a successful, failed 
and canceled percent value.
Next, I created a line chart to show the distribution of each bucket.

https://github.com/Azykan/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png

### Challenges and Difficulties Encountered
Having to re-analyze the original dataset to confirm there were zero canceled plays.
Not using the already filtered datasheets of Successful and Failed from the lesson, 
which required me to write the formulas specifying the filters for plays and outcomes. 
Having to manually alter each Countifs formula for each cell to accommodate each bucket and outcome. I could have overcome it by creating dynamic formulas.  
## Results

- What are two conclusions you can draw about the Outcomes-based on the Launch Date?
The prime months to launch Theater campaigns in May and June.
December is the worst month to launch a campaign
- What can you conclude about the Outcomes-based on Goals?
The lower your funding goal the more successful the campaign is likely to be.
There is a downward trend as the funding goal increases.

- What are some limitations of this dataset?
I did not find any limitations of the dataset for what Louise is looking for. However, not knowing the genre of the campaigns or details about the backers and when they pledged/donated is a limitation. 
- What are some other possible tables and/or graphs that we could create?
Other tables and charts can be created with additional available data like country and campaign duration.





