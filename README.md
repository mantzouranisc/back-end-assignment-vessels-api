# Vessels Tracks API

### Requirements

Your task is to use the dataset supplied to create a **RESTful API** that exposes the following resources:
* vessel
* position
* vesselStatus
* vesselType


##### The API must support
* the following filters: 
  * **mmsi** (single or multiple)
  * **latitude** and **longitude range** (eg: minLat=1&maxLat=2&minLon=3&maxLon=4)
  * **width**
  * **length**
* pagination
* sub-resources
* the following content types:
  * application/json
  * application/xml
  
##### Additional
* Log incoming requests to a datastore of  your choice (plain text, database, third party service etc.)
* Limit requests per client to **10/hour**.
* Include your tests

## The dataset
You will find a csv file that contains the data to use for the assignment in
a reverse-normalized form.

The fields supplied are:
* **id**: unique vessel identifier
* **lat**: latitude
* **lon**: longitude
* **heading**: vessel's true heading
* **course**: vessel's course over ground
* **speed**: speed in knots x 10 (i.e. 10,1 knots is 101)
* **status**: AIS vessel status
* **mmsi**: Maritime Mobile Service Identity
* **callsign**: vessel's Callsign
* **imo**: International Maritime Organization (IMO) number
* **length**: vessel's length (meters)
* **width**: vessel's width (meters)
* **draught**: vessel's draught (meters)
* **type**: vessel's type

_The dataset contains 345 vessels, 37 vessel types, 7 vessel statuses and 3756 positions_

### Share your work
* Stage your solution on a demo page or
* Fork this repo and create a pull request that contains your implementation in a new branch named after you.

**Have fun!**
