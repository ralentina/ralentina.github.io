---
title: "Pharmacy Provision and Povery Rates in Santiago de Chile"
excerpt: "This scatter-plot and map explore the spatial distribution of pharmacies in Santiago de Chile, and its relation to economic inequalities<br/><img src='/images/500x300.png'>"
date: 2020-01-02
tags:
  - Santiago
  - ArcMap
collection: portfolio
---

This scatter-plot and map explore the spatial distribution of pharmacies in Santiago de Chile, and its relation to economic inequalities.  

**Context**
40% of Chilean pharmacies belong to three major chains: Ahumada, Salcobrand and CruzVerde, which collectively control at least 80% of the market (depending on the source, the number varies, from 80 to 95%). These sellers have been involved in collusion and price-fixing scandals (e.g. Serey 2012), and are generally accused of inflating the prices of drugs (Rehbein, 2019). According to a government report, these chains only cover 44% of the country’s municipalities, and appear to concentrate in highly-populated, high-income areas. I was interested in exploring this relation through spatiall analysis. Santiago provides a useful case study, since it is a city largely segregated along income lines, with the wealthier household concentrating in the north-eastern neighbourhoods, and the poorer one in the West.

**Data and Analysis**
To obtain the coordinates of the main pharmacy chains’ stores, I scraped commercial directories using [https://www.crummy.com/software/BeautifulSoup/bs4/doc/](Beautiful Soup). When only the address was provided, I used [https://geocode.localfocus.nl/](this service) to get the coordinates. The data was collected between December 2019 and January 2020. Data about populationa and living density is from the 2017 Census, data about average income levels from the [http://www.sil.mintrab.gob.cl/](Ministry of Work) and data about the poverty levels from [http://observatorio.ministeriodesarrollosocial.gob.cl/casen-multidimensional/casen/casen_2017.php](Encuesta Casen). Each point in the scatter plot represents a municipality. The X axis indicates its average income level, the Y axis the ratio of people:pharmacies. The map is shaded by categorising the municipalities in 4 quantiles, according to the people:pharmacies ratio.

**Results**
Pharmacies are concentrated in the Santiago’s inner neighbourhoods, but once the number of stores is normalised using the number of residents, differences between inner municipalities start to emerge. The Western wealthier neighbourhoods tend to be better serviced by pharmacy chains: the five municipalities with highest income pro capita are also the five municipalities with the lowest ratio of people / pharmacy. The relation between income and pharmacy provision is strongest at the extremes: very poor neighbourhoods tend to lack pharmacies, and very wealthy ones to have a lot, while there is more variability among mid-income neighbourhoods. There are few exceptions among the central municipalities, such as Estacion Central, which is well-served by pharmacy chains despite low income levels.


