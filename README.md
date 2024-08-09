# Advertising Rates Analysis
The purpose of this project was to perform a global analysis for an advertising firm and determine where the firm's advertising is most successful and receives most views, and which is the most popular advertising type. Then with this to discover areas of opportunity for investment and growth for the company.


## Findings (Tableau)
I was able to uncover that the most popular type was video, and  the US is by far the country with highest rates of video advertising. This is particularly significant since despite its larger population, India, which has triple the population size, comes in second. This indicates that population size alone does not account for popularity of video adverts for the firm.

This may be due to the prominence of media and commerce in the United States, and its position as a global media leader is shown in the filtration video popularity across South America.

It also could be the reason behind the success of video in advertising in Western countries which experience media influence. Still, an interesting geographical outlier is India. Similar to the US, media prominence, in this case Bollywood may explain the high rates of video popularity.

<img width="756" alt="Screenshot 2024-08-09 at 10 13 08" src="https://github.com/user-attachments/assets/14af84e5-4485-405c-b95f-00e8d106edb7">


## Business Recommendations
On a financial level, the one of the main suggestions would be to look into the media infrastructure in the countries where video advertising is less successful.  If it's possible to work with telecommunications in those countries to understand the outlook and future plans to have an idea of where to focus advertising investment. 
It would also be useful to understand the cultural habits of those markets t o see which types of advertising resonate more with those populations, such as billboards, written posts and even newspapers in some areas.
This would help to uncover advertising opportunities taking into account the infrastructure and cultural context to be more successful.

Besides that, as the video medium was the most popular advertising type, it's also relevant to see if this would be true for all types of products or only certain ones.
 
From a research standpoint, some of the points alluded to in the previous section would be important such as is the cinematic dominance of the US and India an explanation as to why video advertising is popular.

## Process (SQL-BigQuery) 
Using SQL on BigQuery I used aggregate functions and GROUP BY to collate the data. I then ordered by "max_impressions", and used a limit of 10, to be able to see the top ten countries in the world.

<img width="904" alt="Screenshot 2024-07-31 at 4 05 00" src="https://github.com/user-attachments/assets/59555ce9-9a81-41ee-94da-d9fe163fb907">

