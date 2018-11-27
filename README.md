# ExerciseForAHealthyHeart
Semantic Web - Heart Disease Stroke rate VS Physical Activity Analysis
1. INTRODUCTION
 The main aim of the project is to demonstrate the relationship between cardiovascular health and maintaining a healthy life. We analyzed both the Heart Disease and the Physical Activity data for each state and demonstrated the relationship between the two, based on ethnicity. We have used two datasets in this project, one gives the information about the Heart Disease and other contains information about the Physical Activity rate.
1.1. TOOLS USED
  ● Jena Fuseki Server
  ● Google Visualization API
  ● HTML/Bootstrap/ Java Script
  ● Sgvizler library
    Jena Fuseki server is used as a SPARQL endpoint since there was no endpoint for the datasets used on the data.gov website. Using the Google Visualization API and Sgvizler library, the queried results are rendered to the webpage using JavaScript, HTML and Bootstrap.
    Our project demonstrates results with two visualizations, Geo Map and Line Chart. The results on both the visualizations are based on ethnicity.
    The Geo Map demonstrates the Heart Disease and Physical Activity distribution for each state on the United States Map. We can get the statistics of a state by hovering the mouse over the respective state region.
    The Line Chart demonstrates the pattern or correlation between the Heart Disease and Physical Activity which helps us realize how they are closely connected.
2. TARGET AUDIENCE
  ● This project can be helpful for the Healthcare Communities and agencies to observe the relationship between cardiovascular health and regular physical activity.
  ● The results achieved can be used to demonstrate to the people to help them understand the benefits of exercising on their overall health.
  ● Also, the individuals can use the results as a proof to motivate them to hit the gym regularly.
3. DESCRIPTION OF DATA SOURCES
  3.1 Behavioral Risk Factor Data: Heart Disease & Stroke Prevention (2011 to 2015)
  Page 3 of 6
      ● Source:https://chronicdata.cdc.gov/Heart-Disease-Stroke-Prevention/Behavioral-Risk-Factor-Data-Heart-Disease-Stroke-P/4ny5-qn3w
      ● Format: RDF file
      ● Number of Triples: 2,440,350
      ● Number of Entities in the Data Set: 27
  3.2 Nutrition, Physical Activity, and Obesity - Behavioral Risk Factor Surveillance System
      ● Source:https://chronicdata.cdc.gov/Nutrition-Physical-Activity-and-Obesity/Nutrition-Physical-Activity-and-Obesity-Behavioral/hn4x-zwk7
      ● Format: RDF file
      ● Number of Triples: 1,655,152
      ● Number of Entities in the Data Set: 29
4. RESULTS
  The final results that are obtained after mashing up the two datasets based on ethnicities are demonstrated on a webpage using Sgvizler library and Google’s Visualization API. It can be seen from the results that there is a strong correlation between heart disease diseases and physical activity especially for ethnic groups of White and Hispanic. On the other hand, for ethnic groups like Black and Asians, there is a weak correlation.
  
  
