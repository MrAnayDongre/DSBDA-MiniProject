# DSBDA Mini-Project : Zomato-Restaurant-Rating-Prediction

## Team Members:
<ol> 
  
     PIYUSH BRAHANPURKAR TI06
     ATHARVA DHAYAGUDE TI14
     ANAY DONGRE TI15 
     ANISHA KANGO TI27 
  
     
 </ol>


In this project we have performed exploratory data analysis on given dataset. And created a model that can predict the rating of the restaurant.

 ![Logo](https://user-images.githubusercontent.com/29980448/106356015-2f633200-6322-11eb-9e31-a325549bb76a.png)



## download the dataset from [here](https://www.kaggle.com/himanshupoddar/zomato-bangalore-restaurants)


**Main Objective:**

The main agenda of this project is:

- Perform extensive **Exploratory Data Analysis(EDA)** on the Zomato Dataset.

- Build an appropriate **Machine Learning Model** that will help various Zomato Restaurants to predict their respective Ratings based on certain features.


## Feature description :

1. <b>url </B> contains the url of the restaurant in the zomato website

2. **address** contains the address of the restaurant in Bengaluru

3. **name** contains the name of the restaurant

4. **online_order** whether online ordering is available in the restaurant or not

5. **book_table** table book option available or not

6. **rate** contains the overall rating of the restaurant out of 5

7. **votes** contains total number of rating for the restaurant as of the above mentioned date

8. **phone** contains the phone number of the restaurant

9. **location** contains the neighborhood in which the restaurant is located

10. **rest_type** restaurant type

11. **dish_liked** dishes people liked in the restaurant

12. **cuisines** food styles, separated by comma

13. **approx_cost**(for two people) contains the approximate cost of meal for two people

14. **reviews_list** list of tuples containing reviews for the restaurant, each tuple

15. **menu_item** contains list of menus available in the restaurant

16. **listed_in**(type) type of meal

17. **listed_in**(**city**) contains the neighborhood in which the restaurant is listed


##  Conclusion :

- From the analysis, __'Onesta'__, __'Empire Restaurant'__  & __'KFC'__ are the most famous restaurants in bangalore.
- Most Restaurants offer options for online order and delivery.
- Most restaurants don't offer table booking.
- From the analysis, most of the ratings are within 3.5 and 4.5.
- From the analysis. we can see that most of the restaurants located in '__Koramangala 5th Block__', '__BTM__' & '__Indiranagar__'.Then least restaurants are located  '__KR Puram__', '__Kanakapura__', '__Magadi Road__'.

- __'Casual Dining'__, __'Quick Bites'__, __'Cafe'__, __'Dessert Parlor'__ are the most common types of  restaurant.And __'Food Court'__, __'Casual Dining'__, __'Dhaba'__ are the least common. 
-  From the analysis, __pasta__ & __Pizza__ most famous food in bangalore restaurants. 
- From the analysis, we can see that __North Indian__  Cuisines are most famous in bangalore restaurants. 
-  Two main service types are __Delivery__ and __Dine-out__. 
- From the analysis, we can see that   __'Onesta'__, __'Truffles'__ & __'Empire Restaurant'__ are  highly voted restaurants.

- For the modeling part, i used __LinearRegression__, __DecisionTree Regressor__, __RandomForest Regressor__ , __Supprotvector Regressor__ & __ExtraTree Regressor__. From all these models __ExtraTree Regressor__ perform well compared to the other models.So i selected __ExtraTree Regressor__ for model creation.

