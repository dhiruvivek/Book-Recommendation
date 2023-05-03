# **Project Summary -**
A book recommendation system is a system that suggests books to users based on their interests and preferences. These systems are commonly used by online bookstores, libraries, and reading apps to help users discover new books and authors. There are several approaches to building a book recommendation system. One common approach is to use collaborative filtering, which involves analyzing the reading patterns and preferences of a group of users and making recommendations based on what similar users have enjoyed. Another approach is to use content-based filtering, which involves analyzing the characteristics of a book (such as its genre, author, and subject matter) and making recommendations based on how closely they match the user's interests.

In this project, building a book recommendation system using one or more of these approaches.need to gather a dataset of books and user ratings, and then use machine learning algorithms to build a model that can make recommendations. You may also need to design a user interface for your system, so that users can easily interact with it and receive recommendations. Overall, this project will involve a combination of data gathering, data analysis, and development skills, and will give the opportunity to apply knowledge of machine learning and recommendation systems in a practical context.

## **Understanding the Business Problem**

Businesses may have the following expectations from a book recommendation system:

**Increased sales**: One of the main goals of a book recommendation system is to increase sales by suggesting books that users are likely to purchase. This can be achieved by making personalized recommendations that match the user's interests and preferences.

**Customer satisfaction**: A good recommendation system should be able to provide users with a satisfying and enjoyable experience. This can be achieved by making relevant and accurate recommendations and by providing a user-friendly interface.

**User engagement**: A recommendation system can help to keep users engaged with a business's platform by providing a continuous stream of recommendations and new content. This can lead to increased customer loyalty and a longer user lifespan.

**Improved user experience**: A recommendation system can help businesses to improve the overall user experience by making it easier for users to discover new books and authors that they may enjoy.

**Competitive advantage**: A well-designed recommendation system can provide businesses with a competitive advantage over their rivals, as it can help to attract and retain customers.

Data-driven decision making: A recommendation system can provide businesses with insights into user preferences and reading habits, which can be used to inform marketing and content strategy decisions.

# **Conclusion**




*   In EDA, the Top-10 most rated books were essentially novels. Books like The Lovely Bone and The Secret Life of Bees were very well perceived.

*   Majority of the readers were of the age bracket 20–35 and most of them came from North American and European countries namely USA, Canada, UK, Germany and Spain.

*   If we look at the ratings distribution, most of the books have high ratings with maximum books being rated 8. Ratings below 5 are few in number.

*   Amongst the memory based approach, item-item CF performed better than user-user CF because of lower computation requirements
*   Author with the most books was Agatha Christie, William Shakespeare and Stephen King.


*   For modelling, it was observed that for model based collaborative filtering SVD technique worked way better than NMF with lower Mean Absolute Error (MAE)


*   Handling of sparsity was a major challenge as well since the user interactions were not present for the majority of the books.
*   Understanding the metric for evaluation was a challenge as well


*   Since the data consisted of text data, data cleaning was a major challenge in features like Location etc..
*   Decision making on missing value imputations and outlier treatment was quite challenging as well.




