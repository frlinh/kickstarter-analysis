## An Analysis of Kickstarter Campaigns
___
# Purpose:
Performed data analysis on several thousand crowdfunding campaigns to identify the correlations to successful and unsucessful campaigns.

# Analysis:

### Analysis of Outcomes Based on Launch Date
![Theater Outcomes vs Launch Chart](https://github.com/frlinh/kickstarter-analysis/blob/014cd0fbb744b7b956830d396c71fe780300f2f0/Theater_Outcomes_vs_Launch.png)
### Results
The month of May launched the most successful Kickstarter Theater campaigns.
The month of December launched the least successful Kickstarter Theater campaigns.

### Analysis of Outcomes Based on Goals
![Outcomes vs Goals](https://github.com/frlinh/kickstarter-analysis/blob/014cd0fbb744b7b956830d396c71fe780300f2f0/Outcomes_vs_Goals.png)
### Results
Kickstarter campaigns with a goal of less than 1000 were most succesful.

### Box & Whisker Chart
![Kickstarter Box and Whisker Chart](https://github.com/frlinh/kickstarter-analysis/blob/2e91953608253f74c074ce4f25927a3581932ec9/Kickstarter%20Analysis%20Box%20and%20Whisker%20Chart.png)
### Results
The average campaign goal is 4x more than the average pledged amount.
The median campaign goal is slightly higher than the average pledged amount.

# Challenges and Difficulties Encountered:
### Challenges
The total number of 'Successful' and 'Failed' goals did not add up correctly when I was creating the 'Outcomes Based on Goals' table.  I spotted this when I ran the 'countif' formula on the data from the Kickstarter tab that was greater than 0.  I found that I was missing a row with a goal of '40000 to 44999'. The total numbers matched once I corrected the table and formula in the row.

### Limitations
The limitations in the dataset is the number of campaigns held between 45000 to 49999.  We could not measure the success rate with only one fail campagin in this range.

### Other Outcomes:
We could look into outcomes based on Country and the length of campaigns for a more in depth analysis.
___
