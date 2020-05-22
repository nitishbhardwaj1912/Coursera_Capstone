<p align="center">
  <img width="400" height="250" src="https://upload.wikimedia.org/wikipedia/commons/6/69/EM_Clustering_of_Old_Faithful_data.gif" alt="Clustering">
  </p>
  
<p align="center">
Image reference: [1] 
</p>


# Find Me a Home - Clustering of Toronto Data
This repository contains objects related to the clustering of Toronto, Canada Neighbourhoods based on Crime Rate, Local Employment, Childcare spaces and Nearby venues.

## About Dataset

The data for this research problem is based on various sources. Firstly the data of Toronto neighbourhoods having geolocation details like the Latitude and Longitude is fetched from the “Open Canada Neighbourhood” website[2]. Secondly, data for the home prices, childcare spaces and local employment is fetched from a URL [3] of “Open Canada”. Thirdly, the data for crime-related cases in each neighbourhood is fetched from another UR[4]. At this step, the data contains 140 unique neighbourhoods of Toronto and the other fetched details.

Once we have a single dataset having the geolocation details of each neighbourhood in Toronto, the details of nearby venues are fetched for each location using Foursquare API [5].

The data is then cleaned and processed to have the final dataset ready to feed for the clustering algorithm.

## Business Problem

Whenever somebody migrates to a new place, they instantly start their search for an ideal house. It is generally noticed that a decision to buy/rent a house is highly supported by the location like nearby venues of the house or the crime rate, and local employment rate. The married people having children give preference to places which have nearby childcare spaces. It becomes difficult for a user to find all these attributes. They end up doing their research either by visiting the location or by visiting various websites.

Toronto is a highly populated city in the Ontario province of Canada. It is also considered as the Silicon Valley of Canada. Every month a lot of people do migrate to Toronto in search of better opportunities and a world-class lifestyle.

This project addresses the business problem of the users who are looking for a house in Toronto. The solution will suggest the most common venues near the neighbourhoods as well as the crime rate, local employment rate and several childcare spaces in the area.

## Detailed Project Report can be viewed at this link:
https://shorturl.at/gUY12
<a href="https://nbviewer.jupyter.org/github/nitishbhardwaj1912/FindMeAHome_TorontoClustering/blob/master/Project_Business_Report_FindMeAHome.pdf">Project Report</a>

## Detailed Project Presentation can be viewed at this link:
https://shorturl.at/bhxJP

## Project output, code and analysis performed can be viewed at this link:
https://nitishbhardwaj1912.github.io/FindMeAHome_TorontoClustering/

## References:
[1] "Clustering", wikimedia, 2020. [Online]. Available: https://commons.wikimedia.org/wiki/File:EM_Clustering_of_Old_Faithful_data.gif. [Accessed: 14- May- 2020].

[2] "Open Data Dataset", Open.toronto.ca, 2020. [Online]. Available: https://open.toronto.ca/dataset/neighbourhoods/. [Accessed: 14- May- 2020]. 

[3] "Open Data Dataset", Open.toronto.ca, 2020. [Online]. Available: https://open.toronto.ca/dataset/wellbeing-toronto-economics/. [Accessed: 14- May- 2020]. 

[4] "Open Data Dataset", Open.toronto.ca, 2020. [Online]. Available: https://open.toronto.ca/dataset/wellbeing-toronto-safety/. [Accessed: 14- May- 2020]. 

[5] "Endpoints | Places API", Developer.foursquare.com, 2020. [Online]. Available: https://developer.foursquare.com/docs/places-api/endpoints/. [Accessed: 30- Apr- 2020].

