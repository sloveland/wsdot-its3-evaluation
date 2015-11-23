#ITS 3 Evaluation

### Objective

* Given a provided latitude, longitude and distance, write a Java program which 
prints out the titles of available highway cameras sorted by nearest to farthest 
away from the user's location.

### Resources

* Register and obtain an Access Code for our [Traveler Information API](http://www.wsdot.wa.gov/traffic/api/).
* For the **Highway Cameras** data type, use the REST interface and `GET` the 
`GetCamerasAsJson` Uri to retrieve a list of cameras. 

### Parameters

* For latitude and longitude, use `47.021461` and `-122.899933` respectively.
* For distance, use `2` miles from the above location.