## CS 638 Project Demo
====
Team Member: Shixuan Fan, Yuting Liu, and Zhenyu Zhang

This project is divided into Four stages

### STAGE I WEB CRAWLING
We wrote the web crawlers and parsers to collect data on [YELP](https://www.yelp.com) and [ZOMATO](https://www.zomato.com). 

The data includs roughly 3000 restaurants in four cities: Chicago, New York City, San Fransisco, and Seattle. We collect the fundatmental information, such as telephone number, address, zip code; and also some additional highlights information including delivery services, take out services, outdoor seating and Wifi.

### STAGE II DATA MANAGEMENT
We analyzed the data quality of two tables we got from the Stage I. 

We chose 10 attributes to get the detailed information about what type of values these attributes could be. We also discussed all problems of data quality that exist in our files and that possibly exist in different cases.


### STAGE III BLOCKING
We took two tables from Yelp and Yomato. Then we matched the tuple pairs from two input tabels to output a new table C.

### STAGE IV MATCHER EVALUATION
We created golden data and then used it to find the best matcher and measure the performance of the matcher. 

### STAGE V DATA MERGE AND ANALYSIS
After combining the data from Yelp and Yomato, we performed the ayalysis on the output data.

To see more details, please see at [HERE](https://yuting-liu.github.io/CS638-Demo)
