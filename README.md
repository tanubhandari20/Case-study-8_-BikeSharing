## Bike Sharing Project

In this Project, we are performing the Implementation of the Gradient Boost Regression Algorithm, and using the Classifier Model to Predict the Demand for Shared Bikes in the Dataset.


Bike Sharing Dataset (day.csv)
--------------------------------------------

**Data Set Characteristics:**

 * This database contains 15 attributes

         A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a 
         price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the 
         user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the 
         same system.
         
         A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. 
         The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful 
         business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a 
         healthy state. 
         
         In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine 
         situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once 
         the situation gets better all around and stand out from other service providers and make huge profits.
         
         They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. 
         Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company 
         wants to know:
         
         Which variables are significant in predicting the demand for shared bikes.
         How well those variables describe the bike demands
         Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike 
         demands across the American market based on some factors. 

 * Number of Instances : 730

 * Number of Attributes : 15

 * Attribute Information :

     * Complete attribute documentation :

               1: dteday

               2: season

               3: yr

               4: mnth

               5: holiday

               6: weekday

               7: workingday

               8: weathersit

               9: temp

               10: atemp

               11: hum

               12: windspeed
               
               13: casual
               
               14: registered
               
               15: cnt


Business Goal :
-----------------------
    You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to 
    understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the 
    demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand 
    dynamics of a new market. 


Install
-------------------------------
    Supported Python version
        -Python version used in this Project:3.5+

Libraries used
------------------------------
 * [Pandas](https://pandas.pydata.org/)
 * [Matplotlib](https://matplotlib.org/)
 * [Sklearn](https://scikit-learn.org/stable/)
 * [Numpy](https://numpy.org/)
 * [Seaborn](https://seaborn.pydata.org/)


Run
------------------------------
    To run this Project you will need some Software, like Anaconda, which provides
    support for running .ipynb files (Jupyter Notebook).