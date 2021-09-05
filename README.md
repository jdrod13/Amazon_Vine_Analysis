# Amazon_Vine_Analysis





## Overview of Project
   
   
   
   
   **On this project, I used US Apparel product reviews from Amazon. The main goal was to set a proper plan to analyze if it would be beneficial to subscribe to a Vine program. The Vine review program is a model where customers can get some free rewards if they concede good reviews.  We were able to use PySpark to extract, transform, and load (ETL) the data to an AWS RD.**
   
   

Resources
•	Datasets:
o	US Apparel dataset
•	Technologies used:
o	Google Colab (to run PySpark)
o	Jupyter Notebook
o	AWS S3 and RDS
o	PostgreSQL




### Purpose
     






## Analysis 






**The purpose of this work is to extract the dataset from an AWS S3 using PySpark to transform it and load it to AWS again as our first step in our process analysis. We pulled the data and  downloaded it as the file was a jupyter notebook file, but it was created in Google Colab for PySpark to run.**


TABLA 1


TABLA 2

TABLA 3


QUERY 1

QUERY 2


QUERY 3






**Finally, I worked with the last table called vine_table to perform the Vine program analysis to filter the best reviews and see any significantly more 5-star reviews in the paid and incentivized (vine) program.  As a result, we can conclude that The best reviews were highly voted as helpful.**






Results
•	Paid Vine Program
o	33 total reviews
o	15 5-star reviews
o	45.5% of vine reviews were 5-star
•	Unpaid reviews
o	45,388 total reviews
o	23,733 5-star reviews
o	52.3% of unpaid reviews were 5-star




## Results and conclusion
    
    
    
    
    
    
   **To sum up, the vine program may not be worth enough for the apparel category. There were not many helpful and meaningful reviews that made part of the analysis (total of 33), and there was a percentage of  5-star rated (45%). Similarly to the unpaid reviews, which were five stars rated (52%).  The ratios may be a little misleading as the volume of studies in the vine and non-vine programs vary significantly. We should consider that perhaps we do not want to pay for it as it is not as attractive for the people to give better reviews.**
   
   
   
   



**The analysis helped us conclude that customers don't feel a positivity bias for leaving good reviews in the paid program as there are so few and not so many well-rated. Nevertheless, if we were to analyze further, we could calculate the mean of the star ratings on each program's reviews to see a significant incentive.**



Ultimas tablas






We recommend applying an NLP sentiment analysis to check for the words used in the majority of the reviews. This way, we could see if vine reviews are more touching and detailed, that we can feel customers have an incentive to leave great reviews.
