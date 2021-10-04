# Kickstarting with Excel

  ## Overview of Project
    
  Louise's play, "Fever", has nearly reached its goal amount to start the show. Before the show starts, Louise would like to know how successful other campaigns were. Specifically, when they launched and what their funding goal was to reach their success. I will be conducting my analysis using the Kickstarter dataset on Excel.
    
### Purpose
  In this analysis, I used the Kickstarter dataset to find out when Louise's play, "Fever", would be most successful. Sorting through this data I will look for patterns of success for campaigns and find out what is needed for a successful play. By doing so, gives Louise a more informed decision for when to launch "Fever", and more successful campaigns in the future.
        
  ## Analysis and Challenges
  
### Analysis of Outcomes Based on Launch Date
  There were a total of 4,114 campaigns in the Dataset and only 2,185 in total were successful. When sorting through the data on Kickstarter I filtered the outcome of each campaign by months and outcome. After filtering through the data two graphs were created. One displaying visually the outcomes of each campaign launch date by month.
![OutcomesBasedonLaunchDateGraph](https://user-images.githubusercontent.com/90425412/135737726-a02d5256-1ad5-4930-b392-33cda0b8350f.png)
  The other was specific to the Parent Category 'theater', and what the outcomes were for these theater campaigns.
![Theather Outcomes Based on Launch Date](https://user-images.githubusercontent.com/90425412/135737795-42cc2dfb-dfdd-4f0a-9684-bafb63516c97.png)

  Both graphs had similar results, likely meaning there is a correlation to the success of a campaign and when it is launched. May had the highest success rate for the campaigns in both graphs. Overall, July had the most failures and when filtering for 'theater', the most failures are in May. Interestingly, December is the only month with more failures than successes. However, the launch date is not the only factor in a successful campaign. 
         
### Analysis of Outcomes Based on Goals
  Another factor to a more successful campaign is finding the right funding. By filtering the outcomes of the campaigns and comparing it to the goal amount. I created the graph below to show these results.
![Outcomes vs goals](https://user-images.githubusercontent.com/90425412/135739121-03128d37-b2d6-455d-baf4-f720a37330f6.png)
        
  This data shows failed campaigns often asking for large amounts and smaller goals had a higher rate of success. 100% of goals failed when asking for $5,000 and goals less than $1,000 were the most likely to succeed. 
      
### Challenges and Difficulties Encountered
  One challenge I see with this data is using Excel as the program for this dataset. It can be very limiting when it comes to large sets of data, such as Kickstarter. Additionally, to keep the data current it will need to be automatically updated, and creating the Macros necessary will be very time-consuming. To help this I would transfer the Kickstarter dataset to a different software so it can be more easily updated and monitored.
        
## Results
  After reviewing the data, it became clear there was a pattern to success and its launch date. Based on the data given, Louise would have the likliest success if launched in May, and more likely to fail in July for her show 'Fever'. June would be the second likeliest to succeed in theater campaigns. Avoid launch in December as there are more failed campaigns than successful ones during this month. 
    
  Another noticeable pattern for the dataset was many campaigns failed due to asking for too much in the goal amount. With the IQR of Goal per a successful campaign $3,500 and failed campaigns had IQR double at $8,000. This makes sense, the average theater campaign receives about 46 Backers and $75.80 from each Backer's donation. These two averages when times together create $3,486.8 for each theater campaign, which comes very close to the IQR of the goal of successful campaigns, $3,500. Having a goal amount of $3,500 and no more than $5,000 will lead Louise to more successful campaigns in the future.
    
  However, this data does have its limitation, due to using Excel, formulas limitations (i.e. no MAXIFS/MINIFS without using tedious formulas). This limits my mean value when it comes to finding the actual mean of the goal pledged to campaigns. The closest we can come to an actual mean and median value is using IQR and AVERAGE formulas. Making the data not completely accurate.
Also, the number of rows in the spreadsheet is limited. Meaning, if I wanted to gather more data for Kickstarter Dataset, I would be limit to how much data I can add to the rows of Excel. This is already a large set of data, and if I wanted to expand it I would use a different program like Tableau.
    
  To add more meaning to this Dataset, I would add graphs for Louise to compare what the goal amount was and the outcome for each theater campaign. Create a similar graph and add filters for each country to see how this might affect the data and goal amount needed. The reason I want to add another is to see if different countries have different goal amounts to be successful.  
Also, create a box and whisker plot showing the statistic for the pledge and goal amount and if it failed or succeeded.  This would visually display the IQR for the goal and pledge amounts for the campaigns and show which one succeeded and failed. That way it can become more clear on how successful Louise's campaign 'Fever' will be, and future ones.
