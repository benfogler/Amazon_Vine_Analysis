# Amazon_Vine_Analysis


## Overview of Analysis
The intent of this analysis is to leverage Spark, pgAdmin, AWS RDS and Pandas to perform the ETL process on one of 50 datasets. Using these
items will allow us to determine if there is any bias toward favorable reveiws.


##

* Number of Vine and Non-Vine member reviews
![Vine_members](https://user-images.githubusercontent.com/114610539/218334367-4857d75d-ae8b-4f3b-87e7-6693776c3b21.png)


![NonVine_members](https://user-images.githubusercontent.com/114610539/218334377-412a2e85-f72c-4202-b65e-6630043970bc.png)


* Reviews with 5 Stars that were Vine members
![5_star_member](https://user-images.githubusercontent.com/114610539/218334384-3d0c9ef1-c3a1-4ebf-86b0-5c2be1b0dd24.png)


* Reviews with 5 stars that were not Vine members
![5_star_nonmember](https://user-images.githubusercontent.com/114610539/218334392-40df0a89-cb63-48e5-b053-0f25d18039b7.png)



* Percentage of reviews that were Vine members
![percent_member](https://user-images.githubusercontent.com/114610539/218334404-d3098a9e-abf8-4fac-9d63-87e43a34171e.png)



* Percentage of reviews that were not Vine members
![percent_nonmember](https://user-images.githubusercontent.com/114610539/218334409-dbee007a-c5c4-4642-a727-77e22f414f13.png)


## Summary of analysis
Given the analysis above there does not seem to be a bias in 5 star reviews from members. With members coming in at 40 percent of the total 5 star
reviews and non-members coming in at nearly 52 percent.

Another analysis to see if being a member provides bias to reviews could be seeing if the lowest reviews are mostly given by non-members, or
if there is a equal spread between the two options.
