# Restaurant-Recommendation-System
Using Restaurant Consumer Rating database to predict and recommend top rated restaurants based on user and restaurant profile.

User can also sort the top restaurants accoring to distance based on latitude and longitude values.


## Data
The data were originally from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Restaurant+%26+consumer+data). There are a README and nine csv files in the [data](data/) directory, including five for the restaurant information, three for the consumer information, and one for the ratings:

Restaurants
- chefmozaccepts.csv
- chefmozcuisine.csv
- chefmozhours4.csv
- chefmozparking.csv
- geoplaces2.csv

Consumers
- usercuisine.csv
- userpayment.csv

- userprofile.csv

Ratings
- rating_final.csv

Three ratings (rating, food rating, and service rating) with values of 0, 1, or 2 are given for a restaurant-consumer pair. More detailed descriptions of the data can be found in the README.

## Exploratory Data Analysis(EDA)

## Relation of Restaurant Rating with various factors (Price, Parking etc...)

<img width="367" alt="Screenshot 2022-06-07 at 1 25 09 PM" src="https://user-images.githubusercontent.com/34760210/172327046-11a72b02-67cd-4c0f-ae19-b8a63dc0193d.png">
Conclusion: Ratings of restaurant having lower price range are usually lower than those having a meduim/high priced menu

***
<img width="478" alt="Screenshot 2022-06-07 at 1 25 29 PM" src="https://user-images.githubusercontent.com/34760210/172327107-4055e35b-8ca7-4c49-9f2e-b63eab6dbb86.png">
Conclusion: Restaurants having a vellet parking options have much higher rating than the restaurants not having one.

***

<img width="387" alt="Screenshot 2022-06-13 at 12 30 01 PM" src="https://user-images.githubusercontent.com/34760210/173297482-eff23a4c-8a0e-4a5c-8b7d-04fa1133342a.png">
Conclusion: Restaurants where smoking is allowed have higher overall ratings compared to restaurants not allowing smoking

***
<img width="410" alt="Screenshot 2022-06-14 at 8 18 05 AM" src="https://user-images.githubusercontent.com/34760210/173482863-ba44f24a-37a4-4a52-a930-c2ac73884c58.png">
Conclusion: Restaurants having a full bar have better overall ratings than restaurants not serving alcohol or only serving wine and beer

***

