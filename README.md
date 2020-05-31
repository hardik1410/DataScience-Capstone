# DataScience-Capstone
Week3 directory :  It contains notebook in whihc you can see segmentation and clustering for the places in Toronto, CA. It finds out the most similar places using KMeans. It uses Foursqaure API to get popular places around given neighborhood and cluster them based on the categories of Top 10 places.
 Data used: https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M, Geospatial.csv(It contains latitudes and longitudes).

How to use : You can fork it and create a local copy and work with it using more data or for different places.

finalProject.ipynb: problem is to find places around any neighborhood based on how many people have rated particular place. It used KMeans algorithm to cluster similar places 
based on likes. <br>Data used in notebook contains the following:<br>
	1)	https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M – This page provides postal codes, name of boroughs and neighborhoods.<br>
	2)	http://cocl.us/Geospatial_data - It contains latitudes and longitudes of the boroughs.<br>
	Foursqaure API – This API provides information such as nearby venues with categories, location, likes etc.


