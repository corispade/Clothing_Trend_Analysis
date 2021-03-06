# Women's Clothing Trend Analysis

### Step 1 - Web Scraping 
* Using the Poshmark website to scrape information on sold women's clothing
    - Struggled scraping, found helpful youtube tutorial from Ty Shaikh on how to scrape basic information. Followed along for practice scraping. 
    - https://www.youtube.com/watch?v=0L1uM_18TTA
    - Would like to continue to build from this by clicking into the image links and also creating a browser instance to scroll the pages further.
* Scrape using BeautifulSoup and Splinter
* Gather information on category, brand, size, price, date (need to find this), description, whether new with tags or not, number of likes
* Build a dataframe

Tools: Jupyter Notebook

Libraries: 

Additional Websites: 
* https://medium.com/@tyshaikh/poshmark-reminders-with-python-part-1-f75006d49a41
* https://www.reddit.com/r/poshmark/comments/bmxob6/i_have_monitored_poshmark_sales_for_one_month_and/

### Step 2 - Clean Data
* Clean the dataframe built from Poshmark sales
* Import directly to database
* Build a function to scrape and update database as needed

### Step 3 - Build Database
* Build database schema for easy reference

### Step 4 - Visualize Data
* What are the top categories sold?
* What are the top style tags sold? Word matrix?
* What are the top sizes sold?
* What are the top brands sold?
* What price point per category?
* Price point by brand? 
* Look at difference between luxury and no-name.
* Price point by brand by category? For top brands.
* Is price different between new with tags and used?
* What sells more between new with tags and used? 
* Date that items are sold by category? What categories are most popular at what time?
* Number of likes vs sold? Do you need more likes to sell? 

### Step 5 - Machine Learning Model
* Predict whether or not an item will sell based on details? 
* Features - Category, Brand, Price, Size, Tags, Likes
* Target - Sell or no