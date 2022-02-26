# Data-Analysis-Glassdoor Salary Dataset

Glassdoor is an American website where current and former employees anonymously review companies. Glassdoor also allows users to anonymously submit and view salaries as well as search and apply for jobs on its platform.

## Project Synopsis

>> This repo contains Data Cleaning, Exploratory Data Analysis, and Data Visualization of Glassdoor salary dataset taken from the Kaggle website [Click here](https://www.kaggle.com/).

-------------------------------
## Project Walk-through

### Data Collection

Glassdoor data taken from the Kaggle website consisted of 23 attributes and 956 tuples, the attributes are: Unnamed: 0, Job Title, Salary Estimate, Job Description, Rating, Company Name, Location, Headquarters, Size, Founded, Type of ownership, Industry, Sector, Revenue, Competitors


------------------------------


## Data Cleaning

After collecting the data, I cleaned the cluttering data for it to be usable/readable for the model. Changes I made and what all variables & scripts I wrote:

    * Removed unnecessary columns
    * Parsed numeric data out of salary
    * Made separate columns for the employer for a given dataset of salary and hourly wages
    * Removed rows without salary
    * Parsed rating out of company_text
    * Made a new column for company_state
    * Added a column for if job was at the company’s headquarters
    * Calculated age of the company by transforming Company founded/established year data
    * Made columns for if different skills were listed in the job description:
        -> Python
        -> R
        -> Excel
        -> AWS
        -> Spark
    * Column for simplified job title and Seniority
    * Column for description length

-------------------------------
## EDA {Exploratory Data Analysis}

* All the imported distributions from the data cleaning data-set, I looked at the distributions of the data and the value counts for the various categorical variables.
* Using **Matplotlib & Seaborn**, categorized and crafted a beautiful data visualisation charts & plots
* Below are a few highlights from the *Pivot tables, Barplots & HeatMaps*.

![image](https://user-images.githubusercontent.com/98012611/155754204-ac899207-5593-494a-aa9b-9c6803ddf3ac.png)

![image](https://user-images.githubusercontent.com/98012611/155754457-2b4d2805-6e0d-4f4c-8217-8783b9071dc4.png)

![image](https://user-images.githubusercontent.com/98012611/155754528-c161d6d9-973b-4fc3-8e11-d921e1043207.png)

-----------------


## Resources Consumed for this project & where you can find them:

    Python Ver: 3.9.0
    Packages Used: Pandas, Numpy, Matplotlib, Seaborn, and Wordckoud.

* Matplotlib Documentation: [Click here](https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.boxplot.html?highlight=boxplot#matplotlib.pyplot.boxplot)
* Seaborn Documentation: [Click here](http://seaborn.pydata.org/examples/many_pairwise_correlations.html)
* Wordcloud Documentation: [Click here](https://www.geeksforgeeks.org/generating-word-cloud-python/#:~:text=Word%20Cloud%20is%20a%20data,highlighted%20using%20a%20word%20cloud.)

-----------------------------
