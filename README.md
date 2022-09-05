# Analysis of motor crashes in NYC from 2015-01-01 to 2021-12-31.

The goal of this project is to offer recommendations to reduce the number of deaths and injures in NYC.

Dataset:

https://www.kaggle.com/datasets/nervozny/motor-crash-nyc (originally taken from https://opendata.cityofnewyork.us/)

Also, I used the following information:

NYC Vehicle Registrations of File - End of year 2018  https://dmv.ny.gov/statistic/2018reginforce-web.pdf
Cycling in NYC https://www1.nyc.gov/html/dot/html/bicyclists/cyclinginthecity.shtml




- Pedestrians get killed more often (total for 7 years).

![image](https://user-images.githubusercontent.com/102557512/188428612-a22a7155-c468-4aa3-92ee-73c2c724c8f9.png)


- Which vehicles kill pedestrians more often? 

![image](https://user-images.githubusercontent.com/102557512/188429302-994775c0-c36e-4ad9-abff-ab270f94153d.png) 

It's logical that the major group is automobiles because it is the most numerous category. But which vehicle kills and injures pedestrians on average, regardless of their absolute number. In other words, which vehicle in itself is more dangerous than others? 

- Which vehicle is more dangerous in terms of both killing and injuring pedestrians? 

![image](https://user-images.githubusercontent.com/102557512/188431582-0a9b1d99-f2fe-473a-ada1-485318a03aac.png) 

For averaging I used number of vehicles regsitred in NYC (https://dmv.ny.gov/statistic/2018reginforce-web.pdf and https://www1.nyc.gov/html/dot/html/bicyclists/cyclinginthecity.shtml). This is the data as of the end of 2018 (and bikes 2021), this is not quite accurate, but it's the best I could find. Nevertheless, it still gives a general idea. 

We can see that buses are much more dangerous for pedestrians both in terms of injury and death. The first thing that comes to mind is that it's because I use the number of vehicles and not vehicle-hours which whould be much more correct and which is algo not available online. The buses circulate all day and many cars are parked in parking lots. That would be a good explanation, but taxis also drive all day and their percentage of killings and injuries is the same as automobiles. Anyway, in order to potentially reduce the number of pedestrians killed the recommendation is to learn more about buses and why they are dangerous. 

Interstingly, the ambulances are in second place after buses in terms of harm to pedestrians.

Mopeds rate of injuring is high, while rate of killing is the lowest (probably it's because mopeds are light and usually don't drive fast as well as bikes). In any case, the casualty rate of killed pedestrians is surprisingly high possibly due to imperfect moped regulation.
