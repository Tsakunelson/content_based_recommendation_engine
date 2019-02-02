# content_based_recommendation_engine
Content_based recommendations

Installation

Anaconda 4.5.11 distribution Python 3.6 Download Tensorflow

## Project Motivation
In the previous notebook, we implemented collaborative filtering to make recommendations based on users similarity. However, there were a number of users who did not receive recommendations when using this technique. For this reason, we employ content based recommendations to find relevant items to recommend to users.

In this recommendation technique, we use information that is known about the user or item to make recommendations. This method of making recommendations is particularly useful when we do not have a lot of user-item interactions available in our dataset.

In content based techniques, you are using information about the users and items, but not connections (hence the usefulness when you do not have a lot of internal data already available to use).

![Content based recommendation technique](https://github.com/Tsakunelson/content_based_recommendation_engine/blob/master/content_based_recs.png)

## File Descrition
We have access to three important items that will be used throughout the notebook.

a. movies - a dataframe of all of the movies in the dataset along with other content related information about the movies (genre and date)

b. reviews - this was the main dataframe used before for collaborative filtering, as it contains all of the interactions between users and movies.

c. all_recs - a dictionary where each key is a user, and the value is a list of movie recommendations based on collaborative filtering

For the individuals in all_recs who did receive 10 recommendations in the ![collaborative filtering project](https://github.com/Tsakunelson/User_based_collaborative_filtering_recommendation_engine.git) , we don't really need to worry about them. However, there were a number of individuals in our dataset who did not receive any recommendations.


## Authors, Licensing, Acknowledgements
- By, Nelson Zange Tsaku Licensing

- Code and documentation copyright 2018 the Author's Code released under Udacity License. 
   Thanks to the Udacity Community and Data X Lab members for related support
