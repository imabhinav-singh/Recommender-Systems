# A Comparative Study of Recommender Systems

We have a google play store app dataset that contains information about an app such as its category, rating, number of reviews, size, installs, type, price, content rating, genres and current version as shown in the folowing figure:- 

![App Data](https://github.com/imabhinav-singh/Recommender-Systems/blob/main/AppData%20(1).jpeg) 


We also have a user review dataset that contains user reviews of an app along with the sentiment polarity and sentiment subjectivity of the review given by the user as shown in the foolowing figure:- 

![User Review Data](https://github.com/imabhinav-singh/Recommender-Systems/blob/main/UserReview%20(1).jpeg) 

We define our problem for recommending apps by dividing it into two parts: 
 - First we form clusters of the apps given in the google play store app dataset using appropriate algorithms which are suitable for the given dataset.

 - Then, with the help of certain attributes, we utilise our clusters formed in part one to recommend apps to the user.


_INPUT_ to part one the problem is an app dataset that contains information about the app such as category, genre, ratings, installs, reviews, price, etc.

_OUTPUT_ is a set of clusters of the app.

The above is fed into an _app recommender system_ that suggests apps to a user based on her review on an app. 
_INPUT_ to the recommender system is a user's review sentiment polarity and sentiment subjectivity 
_OUTPUT_ is a set of apps recommended to the user.

The _objective_ of this problem is to study which clustering algorithms that will perform better for this particular modelling of a recommender system.

The methodology is explained in the report.
