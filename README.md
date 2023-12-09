# Title: Book Recommendation System
Recommendation system is one of the top applications in data science. Every consumer requires a recommendation system like Netflix, Youtube & so on. Recommender system is basically piece of code which is intelligent enough to understand users preference.
The purpose of a book recommendation system is to predict buyer's interest and recommend books to them accordingly.
A book recommendation system can take various parameters into consideration for filtering user reviews.

Dataset Descriptions: 
We have 3 files in our dataset that are Books, Ratings, Users. 
**Books**: First are about books which contain all the information related to books.

**Users**: The second file contains the registered users information.

**Ratings**: Ratings contain information like which user has given how much rating to which book.
Here We are considering the average highest rating books given by users for top 50 books. Maybe some books got only 2 votes and they've given 10 rating so avrage rating is going to be 10  so here we have used a criteria Popilarity based recommender system that will consider only those books who got minimum 250 users rating.
