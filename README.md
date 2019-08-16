# recommendation_system_projects
These repository contains different recommendation systems based on real open source dataset.

Q. What is recommendation systems?
A. systems or techniques that recommend or suggest a particular product, service, or entity. 


Two categories of recommendation system based on their approach to provide recommendation.

* prediction problem
* ranking aproblem

Types of recommendation problem

* Collaborative filter
    1. User-based filtering
    2. item-based filtering
* Content-based systems
* Knowledge-based recommenders
* Hybrid recommenders


### Collaborative filter
Collaborative filtering leverages the power of community to provide recommendations. Collaborative filters are one of the most popular recommender models used in the industry and have found huge success for companies such as Amazon.
    
   #### User-based filtering
        if we are able to find users that have bought and liked similar items in the past, they are more likely to buy similar items in the future too. Therefore, these models recommend items to a user that similar users have also liked
   #### Item-based filtering
        If a group of people have rated two items similarly, then the two items must be similar. Therefore, if a person likes one particular item, they're likely to be interested in the other item too.
        
  ######  Cons of  Collaborative filter
      collaborative filtering system is the availability of data of past activity. collaborative filters suffer from what we call the **cold start problem.

### Content-based systems
    recommendations based on a user profile and metadata it has on particular items.
    Example: Netflix.

### Knowledge-based recommenders
    Knowledge-based recommenders are used for items that are very rarely bought.
    Example: Real estate purchase.

### Hybrid recommenders
    Hybrid recommenders are robust systems that combine various types of recommender models. Hybrid systems try to nullify the disadvantage of one model against an advantage of another.