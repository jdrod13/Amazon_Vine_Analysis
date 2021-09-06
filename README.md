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








<img width="623" alt="Amazon analisis" src="https://user-images.githubusercontent.com/81654454/132138655-fbfb4c5e-4761-4f77-b61b-6b88508125d7.PNG">







<img width="634" alt="Amazo 2" src="https://user-images.githubusercontent.com/81654454/132138658-a54a1da1-14cc-4aaf-be33-f148e80ab2c9.PNG">






<img width="590" alt="Amazon 3" src="https://user-images.githubusercontent.com/81654454/132138662-dc174ad2-90ac-447f-8d49-3067b8fe533e.PNG">





<img width="629" alt="Amazon 4" src="https://user-images.githubusercontent.com/81654454/132138667-2f571558-f4e6-4be8-b14d-6504f4979e71.PNG">








<img width="575" alt="Amazon_Que 1" src="https://user-images.githubusercontent.com/81654454/132138715-b1b4c76d-3372-4816-b6db-acdd262134a4.PNG">






<img width="580" alt="Amazonque 2" src="https://user-images.githubusercontent.com/81654454/132138721-ad3ed63d-d30e-4f6d-8ef7-e6a62ef8554a.PNG">







<img width="606" alt="Amazon que 3" src="https://user-images.githubusercontent.com/81654454/132138726-50c4792e-ffdd-45cd-8aa7-0a45f7d79ef9.PNG">







<img width="609" alt="Amazon que 4" src="https://user-images.githubusercontent.com/81654454/132152486-4c88b689-d845-452c-8ea5-e05ed2715065.PNG">






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








<img width="634" alt="Ama_further_analisis" src="https://user-images.githubusercontent.com/81654454/132138624-f8d5b6aa-e0e6-4f9c-9b2b-4917f53e69f2.PNG">








We recommend applying an NLP sentiment analysis to check for the words used in the majority of the reviews. This way, we could see if vine reviews are more touching and detailed, that we can feel customers have an incentive to leave great reviews.
