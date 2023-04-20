# Reducing Flood Risks in Belgrade Area through AI Solutions

This is a collaborative open source project promoted by Omdena Belgrade Chapter.

Belgrade is a city (capital of Serbia) located on the delta of two rivers, the Sava and Danube, with 200 km length of the waterfronts. In recent decade, Belgrade was aﬀected with manyﬂoods, where one from 2014 was devastating. Obrenovac, one of Belgradee municipalities, was totally ﬂooded, over 30000 people were relocated, around 10000 houses were devastated.

Project detailed description: https://omdena.com/chapter-challenges/reducing-floods-risks-in-belgrade-area-through-ai-solutions/

# Objectives

The main objective is the creation of a supervised ML model, based on historical meteorological and hydrological data for the Danube, Sava and other small rivers in the Belgrade area, which will predict possible future floods.

In this project, I was responsible for data exploration and processing. I also worked on the model development, where I used the prophet model for time series forecasting.

Data Collection and EDA (Exploratory Data Analysis)
Data has been collected for three stations (Zemun, Pancevo and Belgrade) mainly from the database from Serbia Republic Hidmet Service.

https://www.hidmet.gov.rs/index_eng.php

![download](https://user-images.githubusercontent.com/65725230/233372885-4a01f381-5405-479f-9da7-16c9ef07cddb.png)

The training data was selected from 2000 to the end of 2019 and the year for 2020 was separate as test set. The flood alert level for Sava river in this is sation is 500 cm, that is, water levels higher than 500cm indicate risk of flood.



The results and error metrics for the prophet model created are in the tables and figures below.


![image](https://user-images.githubusercontent.com/65725230/233374558-5beb480f-cc85-4673-9d8e-52dc67e5cdae.png)
 
![image](https://user-images.githubusercontent.com/65725230/233375544-14dfe019-b26c-45f4-978e-c5e68d411d01.png)


