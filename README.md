# Analysis of Ford GoBike System Data
## by oooo rrrr


## Dataset

> The dataset consists of information regarding 183215 bike-lending records of Ford GoBike System, a bike-sharing system covering the greater San Francisco Bay area, which spans 28 days of February in 2019. The dataset can be found [here](https://github.com/BetaNYC/Bike-Share-Data-Best-Practices/wiki/Bike-Share-Data-Systems).


## Summary of Findings

> In the exploration, I found that bike trip duration has a long-tailed distribution, with a lot of bike trips on the short duration end, and few on the long duration end. When plotted on a log-scale, the trip duration distribution looks roughly bell-shaped, with longest durations around 500 seconds (8.3 minutes). Bike trips occurs during the 9th and 18th hour of the day which are between 8.00 a.m. and 9 a.m. and between 17.00 p.m. and 18 p.m. respectively. During daytime bike trip frequencies are roughly equal while midtime it decreases significantly. The most popular week day for bike trips is Thursday while other weekdays it is slightly lower. However on weekends bike trips are twice as lower as weekdays. Those who are in their the 20s and 30s are predominantly active in bike tripping. Among genders men are almost three times as active as women in enjoying the bike tripping service. Among user types "subscribers" are far more, almost 8 times, valueable clients than "customers" in terms of frequence of using the service. 
> The stations 3, 6, 5, 15, 16, 21, 22, 30, 58, 67 and 81 are the top 11 stations that had most bike outflows and inflows, with 58 and 67 are championing in these regards respectively. The marketing department should pay an attention to this fact. In the meantime, the stations 67, 21, 15, 6, 44, 30, 3, 88, 182 are the top 9 stations that had stockpiled excess bikes and the stations 243, 253, 22, 71, 343, 256, 84, 81, 52 are the top 9 stations that experieced the shortage of bikes, with 67 and 243 extremelely high. Excess bikes shuold be transported to the stations falling short of enough bikes.
> The stations' locations are packed in three major areas with the two biggest relatively closer to each other.
> The most bike trips (337) occured from the station 81 to the station 15.
> The stations 67, 15, 6, 21 and 58 are the top 5 stations that received longest trips while the stations 224, 398, 228, 389 and 300 are the ones that received shortest trips.
> Males experieced the most overall duration for the whole period. And Subscribers are almost 4 times far more solid reasons for the deterioration of the bikes.
> People who are in their 30s and 20s had went for bike trips for way longer durations than other age groups. And average bike trip duration per user in groups does not vary very much, except for those in their 80s and 90s being slightly lower.
> Overall trip durations per day fluctuated and peaked at the end of the period.
> In all the three areas overall shortages and ubundancies of bikes are fairly balanced. Transportation can be done inside each area. we zoomed in to look at from which station to which station bikes should be transported.
> In area A hundreds of bikes should be transported south-west from the stations 67, 21, 15, 44 to the stations 22, 71, 52, 70 and so forth, in area B south-west too from the stations 243, 253, 256, 240 and 163 to the stations 182, 176, 351 and so forth, in area C from the stations 299, 296, 277, 305 and 357 to the stations 280, 317, 281 and so forth.


## Key Insights for Presentation

> For the presentation, I focus on distribution of bike trip durations, distribution what day hours and weekdays bike-renting is most frequent, trip popularity among age groups, top and outsider 20 stations with the number of bikes are inflowing and outflowing.

> Furthermore I show the map of the stations with locations, further zooming in the 3 major stations clusters in the 3 areas, and bike stock status of each station at the end of the period. By doing this I demonstrate real capacity and end-of-the-period bike stocks in relationship with their relative geographical positions. 