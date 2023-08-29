# _Swiggy-Data-Analysis_

This repository contains a capstone group project. Skillfully extracted data from Swiggy's website, including Restaurant Names, Prices, Locations, Cuisines, and URLs. Through adept data cleaning and visualization, gleaned valuable insights that provide a deeper understanding.


<div id="header" align="center">
    <img src="https://github.com/yasmeenustad/Swiggy-data-Analysis/assets/112754746/05bac31e-b6ac-462e-9744-4fd1e09b2225"  height="400" width="800"/>
</div>

## Aim of the Project:
We have observed a trend towards remote kitchens in recent times, and as a data analyst, our task is to identify the best location to start a remote kitchen or a restaurant in Bangaluru based on the demand for different types of cuisines in the area.![image](https://github.com/yasmeenustad/Swiggy-data-Analysis/assets/112754746/f58be107-5ba1-4620-b148-900acbe885bb)

## Objectives:
#### 1. Web Scraping:
We utilized Python libraries such as BeautifulSoup and Selenium to proficiently extract data from the Swiggy website. The scraped data encompassed crucial elements including Restaurant Names, Locations, Two-Person Prices, Cuisines, Ratings, Delivery Review Numbers, and URLs of the restaurants.

#### 2. Data Cleaning:
Recognizing the initial data's imperfections, we employed both Pandas and Excel to execute a meticulous data cleaning process.

##### Handling Null Values:
Addressing the presence of Null values in our dataset, we applied tailored strategies involving the use of means, medians, and modes for specific columns. This approach included filling Null values with the Mode for categorical columns, while employing Mean and Median for numerical counterparts.
##### Price Refinement:
We further refined our data by extracting individual meal prices from the 'Price for Two' column.

#### 3. Data Visualization:
Building upon the cleaned dataset, we derived insightful patterns and trends. These valuable insights were then presented dynamically through an interactive dashboard enhanced with Slicers, providing a comprehensive visualization of our findings.

##  <img src=https://user-images.githubusercontent.com/106439762/178428775-03d67679-9aa4-4b08-91e9-6eb6ed8faf66.gif  width="48" height="48"> Insights:
   
    
    o	Indiranagar has the maximum number of restaurats as 24% amoung all the locations in Bangalore

    o	Burger seignuer is cuisine wise and price_wise an expensive restaurant 
  
    o	Top 3 Locations which is having Maximum number of restaurants where delivery review number is greater than 1000 
             1. Indiranagar 68
             2. Btm Layout 61
             3. Kormangala 47

    o	Indiranagar has maximum number of less rated restaurants amoung all the locations
    
    o	Top 3 cuisines by number of restaunts
             1. North Indian
             2. Desserts
             3. Continental
             
    o        Shanti Nagar has  the highest rating as 4.8 and top delivery number amoung all the Location.     

    o	The top 5 cuisines based on average ratings and average prices for one are:
            1. Keto         4.5 ratings    150 avgerage price
            2. Mexican      4.4 ratings    125 avgerage price
            3. Pan_Asian    4.3 ratings    150 avgerage price
            4. Portugese    4.2 ratings    175 avgerage price
            5. Sea food     4.1 ratings    150 avgerage price

    Indiranagar Dominates Restaurant Count:
Indiranagar stands out as the location with the highest concentration of restaurants, accounting for a substantial 24% of all eateries in Bangalore.

Burger Seigneur: A Luxurious Culinary Experience:
Among all cuisines, Burger Seigneur emerges as an exclusive and relatively expensive dining option, both in terms of cuisine and price.

Hotspots for High Delivery Reviews:
The top three locations with a remarkable number of restaurants, each having a delivery review count surpassing 1000, are:

Indiranagar (68)
BTM Layout (61)
Koramangala (47)
Indiranagar's Range of Restaurant Ratings:
Indiranagar houses the highest number of restaurants with lower ratings compared to other locations.

Top Culinary Preferences:
The top three cuisines by the number of restaurants are North Indian, Desserts, and Continental, indicating their popularity among diners.

Shanti Nagar: Pinnacle of Ratings and Delivery Reviews:
Shanti Nagar showcases the highest average rating of 4.8 along with a notable delivery review count, making it a standout location.

Cuisine Rating and Pricing: The Elite Five:
The top five cuisines, ranked based on average ratings and average prices for one, are:

Keto (4.5 ratings, $150 average price)
Mexican (4.4 ratings, $125 average price)
Pan_Asian (4.3 ratings, $150 average price)
Portuguese (4.2 ratings, $175 average price)
Seafood (4.1 ratings, $150 average price)


## Dashboard:
![Screenshot_20230607_032720](https://github.com/yasmeenustad/Swiggy-data-Analysis/assets/112754746/2806b894-8546-493a-9760-06772aa63913)
![Screenshot_20230607_032734](https://github.com/yasmeenustad/Swiggy-data-Analysis/assets/112754746/0e957bbc-b191-4e5d-acfa-57840b5f6bd4)
![Screenshot_20230607_032040](https://github.com/yasmeenustad/Swiggy-data-Analysis/assets/112754746/2db3d7f9-af35-4392-bf6e-8bf547d2a225)

## Learnings:
1. Web Scraping 
2. New Python Libraries (BeautifulSoup and Selenium) 
3. Time and Team Management





