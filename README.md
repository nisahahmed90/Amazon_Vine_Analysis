# Amazon_Vine_Analysis

## Analysis Overview

This project analyzes Amazon Vine program and determines if there is a bias toward favorable reviews from Vine members.
The analysis uses PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and calculate different metrics.
We focused on the US reviews for video games.

## Results

### Total number of Reviews

- Vine reviews

<img width="462" alt="Vine Reviews" src="https://user-images.githubusercontent.com/100812308/176089591-b2652c06-3e81-4140-ba53-13f74bf464df.png">


- Non-Vine Reviews

<img width="457" alt="Non-Vine Reviews" src="https://user-images.githubusercontent.com/100812308/176089630-4db28867-fd52-4685-aa1f-52aa4092e725.png">


### Total number of 5-star reviews

- Vine Reviews

<img width="725" alt="Vine Reviews- star" src="https://user-images.githubusercontent.com/100812308/176090207-c2ffff81-d6c0-4778-b00f-b576edbf27e8.png">



- Non-Vine Reviews

<img width="632" alt="Non-Vine Reviews- star" src="https://user-images.githubusercontent.com/100812308/176090223-7a52f2bd-bf86-4387-8d91-c64d0dde9ab0.png">


### Percentage of 5-star reviews

- Vine Reviews

<img width="633" alt="Screen Shot 2022-06-28 at 12 09 22 AM" src="https://user-images.githubusercontent.com/100812308/176090464-0c0e6348-aab1-4299-bd98-40916750e927.png">


- Non-Vine Reviews

<img width="675" alt="Screen Shot 2022-06-28 at 12 09 45 AM" src="https://user-images.githubusercontent.com/100812308/176090384-a62d5841-cd4d-4767-bf51-c21064873fca.png">


## Summary

51% of the reviews in the Vine program were 5 stars reviews whereas the percentage in the non-Vine reviews is only 39%. This describes a positivity bias for reviews in the Vine program.
Additionally we could analyse the statistical distribution (mean, median and mode) of the star rating for the Vine and non-Vine reviews.



