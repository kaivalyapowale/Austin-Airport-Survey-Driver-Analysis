# Austin-Airport-Survey-Driver-Analysis
Key Driver Analysis for Austin International Airport Survey Data from 1Q 2015 to 1Q 2017

## About the Data

Data was pulled from https://data.austintexas.gov/City-Government/Airport-Quarterly-Passenger-Survey/dvu8-ztdx

This data is available on data.gov; The home of US Government’s open data. It consists of quarterly surveys of passengers identifying their satisfaction with the airport.
The data contains 37 features and 3501 customer surveys. We have selected this dataset as our final dataset. The survey contains approx 1900 zeros for overall satisfaction. Our analysis aims at understanding what leads to these scores. Most of our data is categorical apart from quarter, and hour_of_flight. We are dealing with a larger number of features and will have to conduct an extensive statistical analysis. The data also contains a number of “no values” in the survey. We will have to deal with missing values by either removing those data points or fill them using some of the data cleaning techniques.

## Problem Statement and Scope
To analyse the customer survey data to identify the Key features that impact passenger satisfaction at the
Austin-Bergstrom International Airport.

+ What is the main marketing or business issue we were trying to address?
The first and foremost step taken in identifying product or service quality is a customer survey. Consumer research helps us understand the level of satisfaction for our customers. When companies take customer surveys, they have various assumptions about different features affecting the overall customer satisfaction. The problem is that they do not know what particular factor of their service actually affects the overall satisfaction and to what extent. So, we are trying to analyze the driving factor for the overall satisfaction that a customer has rated.

+ How would you structure it into an analytical problem?
‘What features are impacting the overall satisfaction and quantifying the relationship between the drivers with the overall satisfaction?’
This would help the airport authority invest in factors/drivers which would improve customer satisfaction

+ Is the project's level of complexity appropriate?
Yes, the project’s level of complexity is appropriate. This includes identifying the various factors, relevant rows, cleaning of the data, and establishing relations between factors. There could also be multicollinearity between different variables which would render them useless. So, identifying the core factors affecting customer satisfaction while looking at the causality seems appropriate.

## Analysis Plan
+ What are the initial hypotheses?
All drivers have equal weight on the outcome variable Our predictors are independent
+ What potential patterns would you like to uncover?
Any major difference between overall satisfaction, 0, 1, 2 & 3 Whether the time of flight affects the overall satisfaction
+ What analytical methods and algorithms do you plan to implement?
Algorithm: Multivariate Linear Modelling


Step 1: Exploring the data - Chi Squared Test, EDA, Correlation vs. Causation
Step 2: Preprocessing - Cleaning, Transforming
Step 3: Descriptive Analysis - Mean, Cross tabulation
Step 4: Hypothesis Testing - Validating assumptions
Step 5: Driver Analysis - Identification

## References and Relevant Work
1. ​https://nycdatascience.com/blog/student-works/increasing-airline-customer-satisfaction/ 
2. ​http://jmm-net.com/journals/jmm/Vol_4_No_1_June_2016/3.pdf
3. ​https://www.nap.edu/read/21937/chapter/2
4. ​https://pdfs.semanticscholar.org/6c51/5a85e733d470a0c0bace37c3d0cdbfe4cf8a.pdf
