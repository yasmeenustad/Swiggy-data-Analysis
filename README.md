# **:Swiggy Data Analysis:**

This repository contains a capstone group project, an extracted data from Swiggy's website, including Restaurant Names, Prices, Locations, Cuisines, and URLs. Through adept data cleaning and visualization, gleaned valuable insights that provide a deeper understanding.


<div id="header" align="center">
    <img src="https://github.com/yasmeenustad/Swiggy-data-Analysis/assets/112754746/05bac31e-b6ac-462e-9744-4fd1e09b2225"  height="350" width="700"/>
</div>

##  <img src="https://github.com/yasmeenustad/Placements-Data-Analysis-Excel-Project/assets/112754746/030e1f21-e04f-4cbd-b301-3576c8c1acc3"  width="48" height="48"> Aim:
We have observed a trend towards remote kitchens in recent times, and as a data analyst, our task is to identify the best location to start a remote kitchen or a restaurant in Bangaluru based on the demand for different types of cuisines in the area.![image](https://github.com/yasmeenustad/Swiggy-data-Analysis/assets/112754746/f58be107-5ba1-4620-b148-900acbe885bb)

##  <img src="https://github.com/yasmeenustad/Placements-Data-Analysis-Excel-Project/assets/112754746/057551de-877a-4a41-916c-d47e81053404"  width="48" height="48"> Objectives:
- **Web Scraping:**
    - We utilized Python libraries such as BeautifulSoup and Selenium to proficiently extract data from the Swiggy website. The scraped data encompassed crucial elements including Restaurant Names, Locations, Two-Person         Prices, Cuisines, Ratings, Delivery Review Numbers, and URLs of the restaurants.

- **Data Cleaning:**
    - Recognizing the initial data's imperfections, we employed both Pandas and Excel to execute a meticulous data cleaning process.
    - **Handled Missing Data:**
      - Addressing the presence of Null values in our dataset, we applied tailored strategies involving the use of means, medians, and modes for specific columns. This approach included filling Null values with the                Mode for categorical columns, while employing Mean and Median for numerical counterparts.

    - **Price Refinement:**
      - We further refined our data by extracting individual meal prices from the 'Price for Two' column.

- **Data Visualization:**
    - Building upon the cleaned dataset, we derived insightful patterns and trends. These valuable insights were then presented dynamically through an interactive dashboard enhanced with Slicers, providing a             
      comprehensive visualization of our findings.

##  <img src=https://user-images.githubusercontent.com/106439762/178428775-03d67679-9aa4-4b08-91e9-6eb6ed8faf66.gif  width="48" height="48"> Insights:

- **Restaurant Distribution in Bangaluru:**
    - Indiranagar stands out with the highest number of restaurants, making up 32% of all locations in Bangalore. This concentration might indicate a high demand for dining options in this area.
<div id="header" align="center">
    <img src="https://github.com/yasmeenustad/Swiggy-data-Analysis/assets/112754746/df4af4ce-b85a-4fb1-a2db-bd092ffce75c"  height="300" width="600"/>
</div>

- **Expensive Restaurant - Burger Seigneur:**
    - Burger Seigneur is a notable restaurant known for its expensive offerings in terms of both cuisine and price. This suggests that it might target a more upscale customer base.
<div id="header" align="center">
    <img src="https://github.com/yasmeenustad/Swiggy-data-Analysis/assets/112754746/fba71f1b-8721-4ec7-872e-8880a79aff09"  height="300" width="600"/>
</div>

- **High-Delivery Review Restaurants:**
    - The top three locations with restaurants having delivery review numbers greater than 1000 are Indiranagar (68), BTM Layout (61), and Koramangala (47). This implies that these areas have a substantial demand for food delivery services.
<div id="header" align="center">
    <img src="https://github.com/yasmeenustad/Swiggy-data-Analysis/assets/112754746/e7f6c309-0126-42e7-9ba9-2470925c5105"  height="300" width="600"/>
</div>

- **Low-Rated Restaurants in Indiranagar:**
    - Despite having the maximum number of restaurants, Indiranagar also has the highest number of less-rated restaurants. This could be due to the intense competition in the area, pushing some restaurants to struggle with maintaining quality.
<div id="header" align="center">
    <img src="https://github.com/yasmeenustad/Swiggy-data-Analysis/assets/112754746/17089fea-e050-4f7b-a3ac-c51caa1a5e18"  height="300" width="600"/>
</div>

- **Popular Cuisines:**
    - Top three cuisines by the number of restaurants:
        1. North Indian
        2. Desserts
        3. Continental
    - This indicates a strong consumer preference for a diverse range of culinary experiences.
<div id="header" align="center">
    <img src="https://github.com/yasmeenustad/Swiggy-data-Analysis/assets/112754746/deb8f390-c6a7-411b-818e-469fd7a0503f"  height="300" width="600"/>
</div>    


- Highest-Rated Location - Shanti Nagar:
    - Shanti Nagar stands out with the highest rating of 4.8 and the top delivery numbers among all the locations.
    - Indicates positive customer experiences in terms of both food quality and delivery service.
<div id="header" align="center">
    <img src="https://github.com/yasmeenustad/Swiggy-data-Analysis/assets/112754746/3bed6d13-993f-4dfb-a8bf-351239d8eb86"  height="300" width="600"/>
</div>
    
- **Top Cuisines by Ratings and Prices:**
  
<div id="header" align="center">
    <img src="https://github.com/yasmeenustad/Swiggy-data-Analysis/assets/112754746/321950e5-43a1-455d-b615-2130840066ec)"  height="300" width="600"/>
</div>

    - The top five cuisines based on average ratings and average prices are:
        | Rank | Cuisine       | Ratings | Average Price |
        |------|---------------|---------|---------------|
        | 1    | Keto          | 4.5     | 150           |
        | 2    | Mexican       | 4.4     | 125           |
        | 3    | Pan_Asian     | 4.3     | 150           |
        | 4    | Portuguese    | 4.2     | 175           |
        | 5    | Seafood       | 4.1     | 150           |
    - These cuisines offer a balanced combination of quality and pricing, making them attractive choices for customers seeking value.

## Dashboard:
<div id="header" align="center">
    <img src="https://github.com/yasmeenustad/Swiggy-data-Analysis/assets/112754746/1d362a9e-9952-44ef-baf7-ff6516a0c8bf"  height="500" width="900"/>
</div>

## <img src="https://github.com/yasmeenustad/Swiggy-data-Analysis/assets/112754746/1334f205-b4ce-4125-b71f-a38637dec197" width="70" height="50" >Conlusions:

- **Observing Localities:**
    - Indiranagar, Koramangala, and BTM Layout are densely populated areas.
    - Few highly-rated restaurants with impressive delivery reviews and limited ratings exist in these localities.
      
- **Promising Approach:**
    - The concept of a remote kitchen emerges as a promising solution.
    - Remote kitchens can leverage the positive delivery review ratings and address the shortage of dining options in these areas.
      
- **New Restaurant Prospects:**
    - A clear opportunity arises for establishing new restaurants.
    - Leveraging remote kitchens could be a strategic approach to cater to the underserved demand.
      
- **Quality Emphasis:**
    - To succeed in opening remote kitchens, a strong emphasis on food quality is crucial.
    - Providing high-quality meals that match customer expectations is a cornerstone of success.
      
## <img src="https://github.com/yasmeenustad/Swiggy-data-Analysis/assets/112754746/603ad77e-2212-4b07-a75a-ffcabb0538f4" width="70" height="50"> Challenges:

- **Challenging Web Scraping:**
    - Scraping Swiggy data proved to be a challenging task primarily due to the dynamic nature of the website.

- **Complex HTML Structure:** 
    - The website's HTML structure was intricate and complex, adding an extra layer of difficulty to the scraping process.

- **Efficient Time Management:**
    - Managing time efficiently was essential to tackle the challenges effectively.

## <img src="https://github.com/yasmeenustad/Swiggy-data-Analysis/assets/112754746/2e256cec-1421-4c5f-9913-052a53dc470f" width="70" height="50"> Learnings:
- **Web Scraping:**
    - **Web scraping** is the process of automatically extracting data from websites. Web scraping allows you to retrieve data, such as text, images, links, and other content, from websites and save it in a structured 
      format, such as a database or spreadsheet.

- **Python Libraries: (BeautifulSoup and Selenium)**
    - **Beautiful Soup** is a Python library used for web scraping tasks. Beautiful Soup is commonly used for extracting information from static web pages where the content is embedded directly in the HTML. It's 
      particularly       useful for projects that require parsing and extracting data from web pages that are not heavily reliant on JavaScript for content rendering.
    - **Selenium** is used for automating browser interactions, making it suitable for scraping dynamically loaded or JavaScript-heavy websites. 






