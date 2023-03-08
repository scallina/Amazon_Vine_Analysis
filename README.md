# Amazon_Vine_Analysis

## Overview
In this analysis, I used Python to analyze a dataset of Amazon customer reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. My dataset consisted entirely of customer reviews written for orders of digital Ebooks. 

## Methods
First, I used PySpark to establish a connection between my Amazon review dataset stored in AWS and my PostgresSQL database. Next, In PostgreSQL, I queried the data needed for my analysis and exported it into Jupyter notebook. Finally, I used jupyter notebook (python) to learn more about how Amazon Vine membership plays a part in customer reviews for digital Ebooks.  

![PySpark](https://github.com/scallina/Amazon_Vine_Analysis/blob/main/Images/PySpark%20screenshot.png)
![PGAdmin](https://github.com/scallina/Amazon_Vine_Analysis/blob/main/Images/pgAdmin%20screenshot.png)

## Results

### Non-Vine customers
- In this dataset, there were 65,149 reviews written by customers who did not have a vine account. 
- 246,73 (37%) reviews published by non-vine users were rated 5 stars. 

![NonVine Reviews](https://github.com/scallina/Amazon_Vine_Analysis/blob/main/Images/Unpaid%20Reviews.png)
![Unpaid 5-star](https://github.com/scallina/Amazon_Vine_Analysis/blob/main/Images/unpaid%205-star.png)

### Vine Customers
- Surprisingly, there were only 6 reviews written by Amazon Vine customers in this dataset; however, they were filtered out before conducting my analysis because they were rated largely unhelpful by other customers. 
![Vine Reviews](https://github.com/scallina/Amazon_Vine_Analysis/blob/main/Images/Paid%20Reviews.png)

## Summary 
Since no helpful reviews were written by Vine program members in the Ebooks department, it's safe to say that Amazon isn't focusing it's program invitations on consumers heavily involved in this market. The reason for that might be that the Ebook marketplace already has a thriving review section where unpaid customers are highly participitory and highly reviewed. 

In future analyses, I'd be interested to learn more about how the review quality changes among Vine users in the print book market. As more and more readers shift to Ebooks, it may reveal that Amazon is driving more review traffic with it's Vine program toward paper book sales. 
