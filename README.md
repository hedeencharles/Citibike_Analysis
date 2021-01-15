# **New York City Bike Analysis**

## **Visualizations**
  * [Click Here](https://hedeencharles.github.io/Citibike_Analysis/index.html) to view <u>visualization website</u>
  * The website showcases three Tableau Stories with similar yet different objectives: 
    * What are the most / least popular Citi Bike stations, since 2016? Can they data help Citi Bike add or remove locations?
    * Number of rides by gender and age, any trends? How can these trends in demographics help expand within the market and maintain clientele as well. 
    * Rides by user type (customer or subscriber). Are Citi Bike customers generally customers or subscribers? What ages fall in each category? Has this changed since 2016? How can Citi Bike utilize this information?

## **Written Analysis**
  * [Click Here](https://github.com/hedeencharles/Citibike_Analysis/blob/main/ANALYSIS.md) to view analysis <u>markdown file</u>
  * [Click Here](https://hedeencharles.github.io/Citibike_Analysis/analysis.html) to view analysis <u>website</u>

## **Softwares used:**
* ### Tableau
  * **Visualizations and Analysis;** visualized uncovered trends and created three Tableau stories for presenting analysis and communicate recommendations. 
* ### Python Jupyter Notebook
  * **Extract;** automated the Notebook to pull in a local directory of CSV files downloaded from [New York Citi Bike Data](https://s3.amazonaws.com/tripdata/index.html). 
  * **Transform;** automated the Notebook to perform data cleaning. This included taking care of missing data, matching datasets that structurally changed over the years (accomplished by removing all spaces and uppercase letters in column names), and 
  * **Load;** automated the Notebook to then concatenate all the CSV files into one DataFrame and exported the DataFrame to a CSV file called 'cleaned_2016_2020_05-10.csv'. This CSV file was then loaded into Tableau for visual analysis.
  * **Exploration;** utilized the Python Pandas and Matplotlib library to further analyze the combined CSV file. Here, I was able to identify outliers and other trends in the data before jumping into Tableau.

  
## **Data Source Citation:**
* ### New York Citi Bike Data:
  * [Documentation](https://www.citibikenyc.com/system-data)
  * [CSV Files](https://s3.amazonaws.com/tripdata/index.html)
  * URL: https://www.citibikenyc.com/system-data