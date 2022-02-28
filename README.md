# An Analysis of Kickstarter Campaigns

Performing data analysis on Kickstarter campaigns to uncover trends in the data
---
#### Overview of Project
  Louise, a close friend needs help setting up a crowd funding campaign to fund her play *Fever*. Louise will need around $12,000 to fund her play.
She has provieded a large raw dataset of kickstarter campaings in Excel for me to further analyize and help her better understand what makes a campiagns succeed.
[Raw Kickstarter Data.xlsx](https://github.com/mattstreet16/Kickstarter-analysis/files/8144217/Raw.Kickstarter.Data.xlsx)
In order to help Louise mirror successful Kickstarter campaigns I needed to impiment some Excel and data analytical skills to create a report that accurately displays trends in successful and unsuccessful kickstarter campaigns in the theater Category and play Subcategory. 

#### Analysis
   I firstly used conditional formatting rules to create a clear visual element to the data sheet that makes it much eaiser to quickly see the outcomes of each campaign.
   
  ![conditional format](https://user-images.githubusercontent.com/99688417/155902646-7b123fdb-4ef9-4f2e-b6f5-e0b16d9868c2.png)
  
After the data was formatted I used the Round formula in Excel to calculate the percent funded, and average donation, created two new coloumns to record my calculations, I then applied the previous conditional formatting rule to the average coloumn
  
  ![Round Formula](https://user-images.githubusercontent.com/99688417/155902863-abda69fb-74a4-455b-ac13-2838f674e938.png)

I then checked if the dates created and dates ended columns were in unix also converted the Unix timestape dates from their number format to an actual readble date to help the data be more easily understood 

![UnixDates](https://user-images.githubusercontent.com/99688417/155909363-c3244a76-9306-404b-9493-088308acd544.png)
![converted-dates](https://user-images.githubusercontent.com/99688417/155909428-80798fe0-d7b5-4fe2-ada7-77cd486ec33e.png)

  Once the data was updated and checked, I used advanced filters, and pivot charts and tables to uncover more specific information from the data set. Further filtering the charts based on country, category, and subcategory reavealed important insights. I specifically filtered data for the United States, the theater Category, and the play subcategory.

![Monthly Outcomes](https://user-images.githubusercontent.com/99688417/155903027-72bd9afb-828e-4328-afb5-fc7e14a8a1e1.png)
![Theater Outcomes by Launch Date](https://user-images.githubusercontent.com/99688417/155903040-74f5756d-8e87-47d4-ba0b-019416a60085.png)
![Parent Category Outcomes](https://user-images.githubusercontent.com/99688417/155903051-a7ed0ea3-701a-4112-8530-0d1e929a9d23.png)

Louise then informed me she wanted more research done on some specific plays in the United Kingdom, so I used a vlookup formula to find and analyize these specifc kickstarters so she could compare them to her own campaign.

![VlookupUKplays](https://user-images.githubusercontent.com/99688417/155903163-9d6a60ab-e5ae-4378-a95d-51a89b2f2a99.png)

Finally with most of the data analyized and I had filtered specific data for plays, I needed to use descriptive data to better uncover trends in the kickstarter plays data set and make a chart that displays any tendencies.

![descriptive data](https://user-images.githubusercontent.com/99688417/155903304-097c9ea5-e23c-4f87-826d-117def94cbc2.png)

Using the descriptive data I could easily create a visual element that shows the distribution of campiagns based on their ential goals and pledges, using this I could see the data was heavily skewed, and I was able to identify any outliers and eliminate them from the dataset.

![Box plot](https://user-images.githubusercontent.com/99688417/155910162-efb8d105-6d82-43d9-93fa-be01ff8861c0.png)

####  Challenges
The main challenge I encountered with this project was the size of the dataset in relation to the relavent data I needed to help Louise. There are countless kickstarter campiagns in many different categories, however much of this information is not needed. What became crucial in my analysis was my use of filters and pivot charts, these excel tools were crucial to my overall analysis.

#### Results
My final Analysis of the Kickstarter campaign allowed me to draw the conclusions that late spring and early summer are the times of year with the most successful Kickstarter campiagns for plays, and further that Louise should lower her goal amount to ensure that her Kickstarter play is fully funded.  
 

