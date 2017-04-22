# *******New York Restaurants Inspection Analysis*********
# Food tastes better when you eat with it's quality at BEST!!

[![](https://cldup.com/dTxpPi9lDf.thumb.png)](http://sumeetusturge.com)

#### ABOUT DATASET
This dataset provides restaurant inspections, violations, grades and adjudication information.This data includes the name and location of inactive food service establishments and the violations that were found at the time of the inspection. Inactive food service establishments include only establishments that are no longer in business or have not operated for an extended period of time. Inspections are a “snapshot” in time and are not always reflective of the day-to-day operations and overall condition of an establishment. This dataset is refreshed on a daily basis.

##### Initial observation on data:
  - Notice, lower the SCORE in dataset better the GRADE of the Restaurant.
  - Various violation code and fixes descripiton to particular code.
  - Many columns contains NaN which needs data cleansing.


#### DATA EXTRACTED USING API
>The link to the API to get the data from NYC website is:
>https://data.cityofnewyork.us/resource/xx67-kt59.json
The key to API is stored as an environment variable and then downloaded the data on local machine.

#### ANALYSIS # 1

* The cuisine of New York City comprises many cuisines belonging to various ethnic groups that have entered the United States through the city.Almost all ethnic cuisines are well represented in New York City, both within and outside of the various ethnic neighborhoods.New York City was also the founding city of New York Restaurant Week which has spread around the world due to the discounted prices that such a deal offers.
* New York City is called as hub for bussiness and there are thousands of people  entering and leaving the city. With so much of happening in the city, it is highly diversified in its own way and we get wide range of cuisine in the 5 Boroughs of the city.
* What if some one wants to try Italian or Mexican food? Well this analysis is all about finding out the where do we find cuisine which is best in its way and has highest rating when it comes to cleanliness and its quality for food and hygine. Below are the analysis results that I found out. I am sure now you will know where to find the cuisine that you love the most in this city of dreams. 

![ana-1 1 queens](https://cloud.githubusercontent.com/assets/25045818/25300449/a8d27180-26dd-11e7-8634-048f48585d83.JPG)

###### We can see that there are 158 Asian restaurants in Manhattan having 17.03 ratings.

![ana-1 1 man](https://cloud.githubusercontent.com/assets/25045818/25300459/e2964fa4-26dd-11e7-80ee-64df896fb5f7.JPG)

![ana-1 1 bronx](https://cloud.githubusercontent.com/assets/25045818/25300460/e296bf02-26dd-11e7-9afd-1ba16156979b.JPG)
###### We can see that there are 158 Donuts restaurants in Staten Island having 11.03 ratings.
![ana-1 1 staten](https://cloud.githubusercontent.com/assets/25045818/25300462/e29843cc-26dd-11e7-90f9-5d87c03122ad.JPG)
###### We can see that there are 18 Korean restaurants in Brooklyn having 19.03 ratings.
![ana-1 1 brook](https://cloud.githubusercontent.com/assets/25045818/25300461/e297c78a-26dd-11e7-85ff-2ab7af93063f.JPG)

```sh
HOVER-OVER THE GRAPHS IN PYTHON NOTEBOOK TO GET INTERACTIVE GRAPHS
```

>Looking at the stats now I exactly know where to find my love for Indian cuisine in NYC without givnig a second thought on the quality. Hope you have found your favourite cuisine. We can clearly say that we can find out American cusinie all over NYC for obvious reasons.

#### ANALYSIS # 2

* New York City comprises 5 boroughs sitting where the Hudson River meets the Atlantic Ocean. At its core is Manhattan, a densely populated borough that’s among the world’s major commercial, financial and cultural centers. Its iconic sites include skyscrapers such as the Empire State Building and sprawling Central Park. Broadway theater is staged in neon-lit Times Square.
* The total land area coverd by NYC is 304.6 mi² which is huge and to find a street where we can get more number of restaurants and have more options is always a cumbersome task for any one who visits NYC. This analysis provide you various popular streets where one can find many options to fulfill their desire of hunger and dont get disappointed.
* Also I have narrowd down this analysis to respective borough. We all know that though the options for food in some streets huge they dont provide you the quality of food that we expect. This analysis gives you the quality of food with number of restaurants.
###### %  distribution of restaurants in NYC.
![ana-4 1](https://cloud.githubusercontent.com/assets/25045818/25300475/3e03b0fc-26de-11e7-8d86-a88a30f8fe81.JPG)
###### We can see that East 161 St has most restaurants with high hygene value in Bronx
![ana-4 2 bronx](https://cloud.githubusercontent.com/assets/25045818/25300474/3e035f8a-26de-11e7-82df-d625e0b03613.JPG)
###### We can see that Penn Plazza has most restaurants with high hygene value in Manhattan
![ana-4 2 man](https://cloud.githubusercontent.com/assets/25045818/25300478/3e04a3ae-26de-11e7-9922-8857cd2762e6.JPG)
###### We can see that Laguardia Airport is with high hygene value but JFK airport has many restaurants with less hygene value in Queens.
![ana-4 2 queens](https://cloud.githubusercontent.com/assets/25045818/25300473/3e0353a0-26de-11e7-81bb-db47a6538d62.JPG)
###### We can see that Atlantic Ave has many restaurants with high hygene value in Brooklyn
![ana-4 2 brook](https://cloud.githubusercontent.com/assets/25045818/25300476/3e04058e-26de-11e7-8845-5cc98216e4b3.JPG)
###### We can see that Richmond Ave has many restaurants but Amboy Rd is having high hygene value in Staten Island
![ana-4 2 staten](https://cloud.githubusercontent.com/assets/25045818/25300477/3e0411fa-26de-11e7-9c02-21439a77f71c.JPG)

```sh
HOVER-OVER THE GRAPHS IN PYTHON NOTEBOOK TO GET INTERACTIVE GRAPHS
```

>Clearly we can see that, there are about 25000 modes of eatable in NYC and Manhattan having the most of it. The color variation gives you how hygine are those restaurants dark red being most hygenic. 

#### ANALYSIS # 3

* As the data set also contains some information about the violation that are captured upon inspecting for various restaurants in different boroughs, there are reviews upon inspecting these restaurants on regular basis. So we will see which borough has violated more number of times and have got an critical remark for their restaurants.
* This analysis was again done based on brough and their result is combined and plotted to compare and for better understanding of the stats. 
* Also, I have plotted out the graph for most violated code and its description overall in the NYC city.
###### Most common and least common violation for food quality.
![ana-2 1](https://cloud.githubusercontent.com/assets/25045818/25300481/5dc81d38-26de-11e7-89bb-a35ee282a8ee.JPG)
###### Comparison with number of critical and non critical inspection results recieved by each borough. Also showing in tabular format.
![ana-2 2](https://cloud.githubusercontent.com/assets/25045818/25300480/5dc7f79a-26de-11e7-8304-6c046c4cd108.JPG)

```sh
HOVER-OVER THE GRAPHS IN PYTHON NOTEBOOK TO GET INTERACTIVE GRAPHS
```

>As we can see that most of the restaurants get critical remark for usage of stored cold food rather than using fresh food. And some violations like Food not protected from potential source of contamination during storage, preparation, transportation, display or service.
Also we can see from the graph that Manhattan being at the top to get critical reviews about the food and Staten Island having the least, may be beacaue it has less number of mode of eatable compared to other boroughs.
