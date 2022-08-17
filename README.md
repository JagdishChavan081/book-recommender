# Data Science Project On Book Recommendation

![home page](https://user-images.githubusercontent.com/54933866/185257397-7b11b723-58bb-4b4f-a789-a541ebb566e8.png)

<p align="center">
Fig1. Home Page
</p>

![recommendation_page](https://user-images.githubusercontent.com/54933866/185257413-bd926658-6abc-41e8-b033-0a7b20c4cdec.png)
<p align="center">
Fig 2Recommendation Page
</p>

### Introduction

The scope of data science solutions grows exponentially each day. Think of it as tools designed to meet your specific business needs and optimize particular business processes. Helps companies make better decisions, and recommender systems help data scientists succeed in it. Recommendations are an integral part of many on-line e-commerce applications like Amazon.com, Netflix, and Pandora. 

### Why Business Needs Recommendation System?
Recommendation System (RS) are tools for business, aimed focused on increasing revenue, profitability and optimizing current product portfolio. The following industries showed a rapid demand-led growth for implementing RS solutions:
•	Retail business: market basket analysis, sequential patterns mining, user profiling, and goods portfolio optimization.
•	Hotel business and tourism: tour and hotel recommendations based on ratings and user preferences.

### Problem Statement

 e-commerce contents available for users to explore are about 70% more than physical. Hence, they need to filter, prioritize and efficiently deliver relevant information. Project focus on design and develop a model with collaborative filtering algorithm with Flask application.

### Solution Developed

Collaborative Filtering (CF) Recommender: involves the generation of books recommendation list for users using the inputs the engine of the CF Recommender performs the computation of similarity among items with other rated items in dataset for a given user using an adjusted cosine similarity model given as: 

𝒔(𝒊,𝒋) = ∑(𝑹𝒖,𝒊−𝑹𝒖)(𝑹𝒖,𝒋−𝑹𝒖) /(1/2(𝒖𝝐𝑼 (𝑹𝒖,𝒊−𝑹𝒖)𝟐 𝒖𝝐𝑼 (𝑹𝒖,𝒋−𝑹𝒖)𝟐 𝒖𝝐𝑼)) 

 s(i,j) represents the similarity score between a given item i  j in the rating system.
 𝒖𝝐𝑼 represents every user u in a set of users U. 
𝑹𝒖,𝒊 is the rating user u gives to item (book) i. 
𝑹𝒖 represents the average rating user u gave for all items user u rated.
 𝑹𝒖,𝒋 is the rating user u gives to next item (book) j.
 When the similarity index is computed and results are obtained, quick sort algorithm is applied to sort the rated items in ascending order. And finally the results are forwarded into the user profile base.
 
 ### Improvement to the Solution
Future works should target on securing recommender system 
### Link to Working project demo/ prototype developed
GitHub Link:- https://github.com/JagdishChavan081/book-recommender
