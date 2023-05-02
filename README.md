# Amazon_Vine_Analysis


Overview 

This project analyzed the Amazon Vine program to see if there was any bias toward favorable reviews from members of the Vine program.  In order to successfully conduct this analysis, we used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and calculate different metrics.  


Results

After the analysis, we were able to determine there was a total of 94 Vine reviews and 40,471 non-Vine reviews.  There was a total of 48 Vine 5-star reviews and 15,663 non-Vine 5-star reviews.  We were able to calculate that 51% of the Vine reviews were 5-star and 38% of the non-Vine reviews were 5-star. 


Summary

The data shows that there appears to be a positivity bias for the reviews in the Vine program vs non-Vine reviews, based on the percentages of 5-star reviews.  Since we are comparing 94 data points to 40,471, another possible analysis could be looking at summary statistics of the Vine members vs non-Vine participants. 
