# TravelApp
Travel Application useful for Tourist

Travel Application - Sample code files
---------------------------------------
The Application aims at helping the Tourist to 
1) Find Places of Interest
2) Review the Ratings and Save a new Rating / Review
3) Ability to see the images of the Point of Interest
4) Ability to see the details of the Point of Interest
And many helpful tips and pointers, extensions from a Traveller perspective.

(Sample Code files of the Application - Few code files of the Project)

Using the data from Google places https://developers.google.com/places/web-service/search 
The Application saves places based on city and performs the CRUD operations on them.

Implementation Details
----------------------
1) The City list with places based on city, combo to select the city and show places only from that location
2) The list is populated by doing a search within 5km radius. 
   The results are placed in db and on a future search, the existing ones are matched.
   The data is overriden only if the user did not change the data from your app. 
   On first edit on a place the details are fetched using the details api.
   
The CRUD operations are implemented on each of these places, Respective Images from Google Places API are also shown.
Various filters on the list, the fields are implemented from the Traveller's perspective
In list view a map with all the places is also shown. 

Technologies used: 
------------------
1) PostgreSQL 
2) Jetty & Tomcat Application Server
3) GWT 
4) Javascript, HTML, CSS
5) Guice dependency Injection
6) JPA - ORM framework
