[![forthebadge](https://forthebadge.com/images/badges/uses-html.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com)


# About the project
This project aims to show the results based on the data that is scraped from the Zomato using Flask and ML.

### Aim
  - In this Project we will take 3 inputs from the user namely Cuisines, Location , Price for one and based on the input provided we have to show Popular Cuisine, Avg       Price for one and most popluar restaurant in that area and then the most popular restaurant that is serving the same Cuisine as you provided
  - Moreover, we need to recommend price and location (based on the input) if the user needs to open a restaurant. For recommendation part ML models were used 
 
### Tech Stack used:
   - Python(Flask, Pickle, Pandas, Numpy)
   - Machine Learning Models(Logistic multinomial Regression)
   - HTML, CSS
   - Canvas

### Prerequisite
  - You would need data from Zomato webpage using web scraping (That is already done and provided as an excel file in the repository) 
  - For this project VS-code IDE was used 
  - You would have to install flask (pip install flask) by clicking on the terimal in VS-code and after that you have to install virtual env too by using the same           command (pip install virtualencv)*
  - After that you would have to activate the env, you can follow this [video](https://www.youtube.com/watch?v=Z1RJmh_OqeA&t=1889s) for the first 6:30 sec for more           clarity
  
### Pandas 
  - Project can be divided into two parts, one is the infomration that we have to provide bases the input and the second one is recommendation model 
  - So we first import the file in app.py (that we created from web scraping)
  - Make some changes in the file using Pandas (like explode function ect) so that data could be molded as per our need to get the desired output

### ML 
  - As we had to give recommendation of Location and Price for one, two models were created,
  - Now as ML model only takes interger values, Cuisine and location input had to be converted into int and then given to the model for prediction
  - Then again change the resule that was in int to string so it can be shown on the webpage
  - For the models two Logistic multinomial Regression models were made as we had to choose location from the given locations 

### Flask
  - Flask is used to deploy the project 
  - Connection had to be made between Python and HTML page with the use of Flask

### HTML 
  - As we are using Flask we need HTML page that takes in the input 
  - Gives it to the python Programm and get the result 
  - Then we need to show the result back to the webpage

#### WEBPAGE:
  When you run the code present in app.py, below webpage will open, in the input column you have to give the inputs and click on submit

![image](https://user-images.githubusercontent.com/117629056/202847003-baac1976-2ad5-4500-b701-993d2b912115.png)


After clicking on submit the page shown below will open and you will be able to see all the information



![image](https://user-images.githubusercontent.com/117629056/202847087-590a7560-d356-4105-a5b8-68cf60967bfe.png)


### Conclusion 
  - This project aim was to show how deploy the ML model and there were a lot of challenges that were faced in making this Project,Learning Flask , HTML from scratch       and applying them, taking decision as to what would be the best ML model etc but finally the project was ready and showing the result as per thr requirments 

If you do face any issue, feel free to reach me
 

