Books to Read Goodreads Data 

# Background 

This project represents one evening spent writing Python pandas code to analysis my Goodreads "To Read" list. I plan on revisitng this to add matplotlib visualizations and clean up the code. 

As an avid reader, I found myself with over 500 books shelved as "To Read" in Goodreads. It was proving challenging to sort this list in such a way to find my next reads. I'm hoping to use my Python skills to solve this problem. 

# Dataset 

This dataset was exported from Goodreads. I excluded books that I've already read and focused on the unwieldy "To Read" List. I began using Goodreads to record my TBR list beginning in 2021. 

# Data Cleaning 
* Dropping columns not needed for analysis
* Checking for duplicates

# Data Analysis 

* Average Rating: 4.01
* Average Page Number: 366
* Median Publication Year: 2015
  *(Average Publication year was 1998 due to Epic of Gilgamesh publication date of 1200 BC)
* Max Page Number: 1327
* Max Rating: 4.88

* Data Manipulation

I placed Average Rating, Number of Pages, and Original Publication Year into bins based on percentiles, in order to better filter the data. 

<img width="639" alt="Screen Shot 2025-02-20 at 8 13 19 PM" src="https://github.com/user-attachments/assets/7809bdd4-5335-4e4b-978f-e62541212e25" />

Then, I could filter the dataset to match certain criteria. I started with Very High Rating, which resulted in 111 rows. 

I tried Very High Rating and Very Recent, still giving me 25 rows. 

When I filtered by Very High Rating, Medium Page Length, Very Recent, I had two options to chose from. These filters can be used to narrow down book options based on rating, page number, and publication year. 

<img width="1132" alt="Screen Shot 2025-02-20 at 8 16 39 PM" src="https://github.com/user-attachments/assets/4214feac-bac9-4aac-8ab7-14fb13866e5d" />

For example, I next filtered for options that are Very High Rating, Very High Page Length, and Very Early Publication Year, which produces 5 options very differnt than the previous search results. 

<img width="1128" alt="Screen Shot 2025-02-20 at 8 17 57 PM" src="https://github.com/user-attachments/assets/6aefb4ec-aef3-4bdb-9d4c-cacd4efc22bc" />



  




