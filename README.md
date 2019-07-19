# Battle of Neighborhood:Coffee, Subway and Sushi
## Introduction
Let's assume we are about to move to New York City. We've found 3 apartments at approximately the same price.
<br><br>
**The task is to decide which address is the most favourable to live in according to these criteria:**
- proximity to subway stations
- proximity to coffe shops 
- proximity to sushi restaurants (can't live a week without a Californa roll!)
The proximity factor is defined as the 500 meters (~1/3 mile) radius.
<br><br>Using FourSquare data, we will identify the points of interest in the vincinity of each address, plot them on a map Folio and draw the conclusion using the scoring method below.

## Data
We've found 3 apartments at approximately same price at these addresses:
- 49 First Ave, New York, NY 10003 
- 22 Cornelia St, New York, NY 10014
- 167 Hester St, New York, NY 10013
To undrestand what points of interest are located within 500m radius of each address, we will use <a href="https://developer.foursquare.com/docs/api">FourSquare places API</a> 

### Methodology
Scoring method:

|Point of Interest|PoI Score|
|-----------|------|
|Subway stop|5     | 
|Coffee shop|3     | 
|Sushi Rest |2     | 
### Methodology

A total score for each address is calculated using the formula:
<br>total score = sum((number of points of interest)*(PoI score))

### Results
|Address|Coffee|Subway|Sushi|Points|
|---|---|---|---|---|
|22 Cornelia St, New York, NY 10014| 38|5|27|193|
|167 Hester St, New York, NY 10013|32|5|11|143|
|2	49 1st Ave, New York, NY 10003|35|1|16|142|

The address of 22 Cornelia St, New York, NY 10014 has come on top 

### Discussion


### Conclusion

section where you conclude the report.
