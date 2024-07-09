# COVID waste water prediction
## can you use waste water to predict COVID-19 outbreaks?
============================================================
Using open data from NYC waste water reports 
And open data from NYC COVID infection information. 
the goal is to develop a model that can use the waste water information to predict and outbreak
this is achieved from using statistics, data visualization, exploratory techniques 

### project organization
  Data- 2 csv files
  1. COVID-19_outcomes
  2. SARS_CoV-2_concentrations

  Jupyter Notebooks- in numbered order
  1. prediction and data cleaning
  2. data exploration
  3. 3.1 modeling attempts
  4. 3.2 time series split to model the data
  5. raw complete analysis notebook contains one complete analysis of the project

  Slide report- final presentation pdf

## solution
### use open data from NYC waste treatment plants to predict outbreaks of COVID in NYC

## data
NYC has 14 waste water treatment plants that covers all neighborhoods of NYC.
NYC also has data on COVID testing numbers and outcomes across the neighborhoods.
The waste water can be tested for COVID genetic material. 
This genetic material can be found in people if they have the virus and is present while asymptomatic

# cleaning and wrangling
for each CSV file we need to 
  1. inspect the data
  2. remove or replace any null values
  3. reformat the dates to the same format
  4. remove and unecessary or duplicate columns
  5. prepare both data sets to have a similar window of time

     
# EDA
after the data is wrangled
  1. we want to graph the data
  2. merge the data frames into one
  3. look for correlations


# algorithms and machine learning
we then want to build a model to try and predict out breaks using the waste water as the dependent variable and the

# modeling issues
after trying multiple models nothing produced accurate scores

splitting the data into a time series model produced poor results

using decision tree classifier, random forest classifier, AdaBoost classifier, KNN classifier all produced poor accuracy

using gridsearchCV to find better parameters for KNN or random forest created poor accuracy

# conclusion
it is not possible to predict future covid outbreaks using waste water

# future consdierations

a larger data from the CDC might produce stronger results due to more data across the USA

rural populaiton would be misrepresented due to lack of public sewers

the general public might not want the govenrment monitoring waste water which may be perceived as government over reach.

# thanks
special thanks to my mentor Rahul Sagrolikar for his patience and guidence
