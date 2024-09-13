The presentation slide deck is saved as SpaceX-Project-Results-Report-SupriyaJ.pdf

**Winning Space Race with Data Science: IBM-Applied-Data-Science-Capstone-Project**
**Problem Statement:**
In this project, I am a data scientist for Space Y, a company aiming to compete with SpaceX, founded by billionaire Allon Musk. SpaceX significantly reduces launch costs by reusing the Falcon 9's first stage, which plays a crucial role in the launch. However, whether the first stage can be reused depends on several factors like payload, orbit, and mission requirements. My task is to predict the likelihood of the first stage landing successfully using public data and machine learning, enabling Space Y to estimate launch costs more accurately and compete effectively with SpaceX.
**Objective:**
The objective is very clear. I have to evaluate the viability of the new company Space Y to compete with Space X.
**Desirable answers:**
The best way to estimate the total cost for launches, by predicting successful landings of the first stage of rockets; and where is the best place to make launches.
**Methodology:**
1.	Data Collection from two sources - i) SpaceX API & ii) Web scrapping from Wikipedia
2.	Data Wrangling - Collected data was enriched by creating a landing outcome label based on outcome data after summarizing and analysing features
3.	EDA using SQL & Visualization
4.	Machine Learning Predictive Analysis using Classification Models - Data that was collected until this step were normalized, divided in training and test data sets and evaluated by four different classification models (Logistic Regression, Support Vector Model, Decision Tree & K Nearest Neighbours Model), being the accuracy of each model evaluated using different combinations of parameters.
**Results:**
•	Space X uses 4 different launch sites;
•	The higher the number of flights at a launch site, the greater the success rate at that site.
•	The launch success rate increased from 2013 to 2020.
•	The orbits ES-L1, GEO, HEO, SSO, and VLEO had the highest success rates.
•	KSC LC-39A had the most successful launches among all the sites. 
•	Using interactive analytics was possible to identify that launch sites use to be in safety places, near sea and have a good logistic infrastructure around
•	Predictive Analysis showed that Decision Tree Classifier is the best model to predict successful landings, having accuracy over 89% and accuracy for test data over 83%.
