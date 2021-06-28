A median is defined as a number separating the higher half of a data set from the lower half. Query the median of the Northern Latitudes (LAT_N) from STATION and round your answer to  decimal places.

Input Format

The STATION table is described as follows:

Station.jpg

where LAT_N is the northern latitude and LONG_W is the western longitude.

Current Buffer (saved locally, editable)    
 
 
10
/*
11
Enter your query here.
12
Please append a semicolon ";" at the end of the query and enter your query in a single line to avoid error.
13
*/
14
SELECT ROUND(MEDIAN(LAT_N), 4)
15
FROM STATION;
16
