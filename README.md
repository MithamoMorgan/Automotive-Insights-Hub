# Automotive-Insights-Hub

![](https://github.com/MorganTheAnalyst/Automotive-Insights-Hub/blob/main/Code%20%26%20CSV_Files/Images/WhatsApp%20Image%202024-07-27%20at%205.56.03%20PM.jpeg)
## Introduction
Welcome to the Automotive Insights Hub your gateway to unraveling the mysteries of the Kenyan automotive industry.
In this digital realm, I harness the power of data to uncover trends, make discoveries and drive informed decisions.
## Objective
The objective of this analysis is to investigate the pricing patterns of cars in Kenya across various brands and models. By thoroughly analyzing data on car prices, models, and brands, this study aims to offer valuable insights that can empower consumers to make well-informed purchasing decisions. Additionally, this analysis seeks to identify market trends and price variations to aid dealers in strategic planning and competitive positioning.
## Tools
* Python: Webscraping,Data Cleaning and exploratory data analysis(EDA).</br>
* Libraries: Pandas (Data manipulation), NumPy (Numerical computing), Matplotlib (Data visualization)
## Data Collection
I scraped data used in this project from [kai and karo motors](https://www.kaiandkaro.com/) a trusted car dealer destination for a wide range of cars in Kenya.
Here is the [code](https://github.com/MorganTheAnalyst/Automotive-Insights-Hub/blob/main/Code%20%26%20CSV_Files/kai%20_karo%20_data_scraping.ipynb).</br>
My data has 10 columns:
* Vehicle: Car make and model name</br>
* Manufacturer: The make of the car</br>
* Model: Specific car model</br>
* Transmission Type: System in a vehicle that transmits power from the engine to the wheels
* CC: Total volume of all the cylinders in an engine</br></br>
* Year: The year the car was manufactured</br> 
* Car Age: The age of the car to date</br>
* Usage Origin: Location where the car was previously used</br>
* Price: The actual price of the car
* Price Range: 
## Data Quality Check
* Check for missing values
* Check for duplicates
* Validate data types
* Check for logical consistency<br>

->Here is the [code](https://github.com/MorganTheAnalyst/Automotive-Insights-Hub/blob/main/Code%20%26%20CSV_Files/Data_Preprocessing.ipynb) to the cleaning process.
## Key Questions:
1.Which car make is most common?</br>
2.How has distribution of car prices varied over the years?</br>
3.What is the average engine displacement across different car make?</br>
4.What is the average price of cars based on their usage origin?</br>
5.Which car make has the highest average price?</br>
6.Is there a correlation between engine displacement and price?</br>
7.Is there a relationship between age of the car and price?</br>
8.Is there a trend towards larger or smaller engine displacement over the years?</br>
9.Which manufacturers have a widest range of price for their cars?</br>
## Data Analysis
The key objective of this stage was to get the answers to the above questions.
Here is the detailed [code](https://github.com/MorganTheAnalyst/Automotive-Insights-Hub/blob/main/Code%20%26%20CSV_Files/Data_Analysis.ipynb) for the analysis.
## Findings
The most common car make is Toyota with 331 models,followed by Nissan with 143 models and thirdly mazda 131 models.

The price of cars tends to increase by approximately Ksh 203,920.88 each year from 1979 to 2024. This positive trend suggests that over this period, the average price of cars has been growing.

The average price of cars by origin is Ksh 3,463,466.98 for foreign used cars which accounts to 61.2% of the average total price and Ksh Ksh 2,195,917.30 for Kenyan used cars accounting to 38.8%.

Range rover has the highest average price of Ksh 8,107,691 followed by Land Rover with Ksh 7,282,352.

The correlation between engine displacement and price is 0.531. This indicates a moderate correlation, it’s not a perfect correlation (which would be 1.0).This means that while there is a general trend that larger engine displacement tends to be associated with higher prices, there are exceptions and other factors influencing price as well.

A correlation coefficient of -0.403 between price and car age suggests a moderate negative relationship. This means that as the age of the car increases, the price tends to decrease, though the relationship isn't extremely strong.In practical terms, it implies that older cars generally cost less, but there are other factors influencing the price as well.

The engine displacement of cars tends to increase by approximately 9.85 cc each year from 1979 to 2024. This positive trend suggests that over this period, the average engine displacement of cars has been growing.

Once again Land Rover and Range Rover have the widest range of price for their cars with Land Rover coming first with a range of Ksh 21,300,000,followed by Range Rover with Ksh 15,850,000
