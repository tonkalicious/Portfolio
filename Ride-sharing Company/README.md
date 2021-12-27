# Project: *Ride - sharing company in Chicago*

![image](https://user-images.githubusercontent.com/81360033/147462725-d1c23792-ed7c-4507-bcc0-d11a4ae3e1de.png)

[View full project](https://github.com/tonkalicious/PortfolioPracticum100/blob/caf74b8cf934a3a272b85d0bde4d5691b0ac5bc6/Ride-sharing%20Company/Ride-sharing%20company%20in%20Chicago.ipynb)

## Tools I used:

![image](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white)

## Project description:

I am working as an analyst for a new ride-sharing company that's launching in Chicago. My task is to find patterns in the available information. I need to understand passenger preferences and the impact of external factors on rides.

[Skip to the general conclusion](#Generalconclusion)


**Step 4. Exporatory data analysis**

![image](https://user-images.githubusercontent.com/81360033/147452245-33c6d930-b711-4b88-bfd3-92777529c3a2.png)

![image](https://user-images.githubusercontent.com/81360033/147452292-b9b2c2dd-d83e-4f7d-884d-ff0770241c50.png)

**Step 5. Testing hypotheses**

![image](https://user-images.githubusercontent.com/81360033/147452346-d5928d65-9cd7-46cb-af08-e91198924173.png)

![image](https://user-images.githubusercontent.com/81360033/147452361-80c959e2-67ab-4339-ac06-c818edfa1d3f.png)

![image](https://user-images.githubusercontent.com/81360033/147452394-42da904d-0bd7-480b-aa8e-b0125b7d881d.png)


## General conclusion:
<a id="Generalconclusion"></a>

There is an impact of weather on ride frequencies. There are 882 rides during good weather and only 180 rides during bad weather; 83% of rides during good weather and 17% of rides during bad weather. The statistic comes from 4 days in November. It would be useful to know statistics on average rainy days throught Noveber; it is around 10 days. The rest of 20 days are without rain or snowfall. You could check the statistics on rainy days on this [link](https://weather-and-climate.com/average-monthly-Rainy-days,Chicago,United-States-of-America).

It is most likely that the average duration of a ride during good and bad weather changes. Still, on November 11 at 10am there were 48 rides and average duration of a ride was 1445 seconds. At 6pm there were 12 rides and average duration was much higer than at 10am; 2580 seconds. The weather during every ride on that day was good. This means it is possible that there is another reason which affects duration of a ride.

It would be helpful to have more parameters on every ride. For example; the distance the car traveled, some checkpoints during the ride (pick_up and drop-off location and some in between), conditions on the road (accidets, road works, fog), time of sunrise, time of sunset, type of traveling that customers use, retal points or starting points of taxies, type of charging and so one.

Correlation between number of rides and duration of rides is very strong. The higher the number of rides in an hour, the higer duration of rides.

It would be useful to know what kind of service did customers use, taxi, car-sharing or something else. Then we could see is there any correlation within these parameters.





