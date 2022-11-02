# Amazon_Vine_Analysis
## Purpose of the analysis
The main objective is to analyze the Amazon´s qualifications and comments from different clients. This is very important because it allow the company to know how satisfied are the clients, in addition, it may allow to take decisions on what products we want to sell or maybe we have to remove some of them from the store. 
In the other hand, the clients can also see the comments before buying the item, which will give a better idea of what to expect. 
The main challenge here is that even if we don´t have a lot of products variety, a single product can receive billions of comments and opinions, now, 2 or more products might have billions or comments and we have to work with them, that´s why we are using Google Colab and Spark.


## Results
We have a huge amount of information, so it is important to clean it a little, i.e. we can just consider the comments within a certain value, like that, we start looking for trends and not just for a comment that migth represent a very bad opinion (or very good) of a product and affect its reputation. 

![more than 20 votes](https://user-images.githubusercontent.com/108499271/199618804-b49a416a-1150-4ac0-aef6-ecd6a74ea2d5.png)

Now, we can consider the ones with Vine and see how it is affecting the ratings:

![vine_review_five](https://user-images.githubusercontent.com/108499271/199621976-0b3e5af9-3e3f-4857-b6ac-1b2d96856623.png)

We have 26661 votes with 5 star ratings and also with more than 50% percentage between helpful votes/ total votes, which is a considerable amount of good references and comments. 

on the other hand, we have 3762229 votes without vine, but on the same conditions we just mentioned. That is showing also very good comments but without vine, which is not what we expected. 

![vine_review_no_five](https://user-images.githubusercontent.com/108499271/199622577-563391b7-62e3-4bd1-85b6-12cb77c1a249.png)

## Summary
We can see that most of the votes and comments came from non-vine, 5 star ratings included, not all of them are from vine voters. In addition, we can observe a very good 5 star rating overall. Througt the mentioned tools we can build any kind of tables we want, as shown 

![review_id_table](https://user-images.githubusercontent.com/108499271/199623621-60417236-2a18-4939-9e03-efe07d4adb82.png)


![customer_table](https://user-images.githubusercontent.com/108499271/199623631-b5ad1510-187d-44bb-a283-525ae6a09148.png)


![Vine_table](https://user-images.githubusercontent.com/108499271/199623645-907a0d10-b34b-4892-822b-bb1778e02182.png)



