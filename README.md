# Mobile price prediction

![89472772-man-talking-beside-phone-with-blank-screen-](https://user-images.githubusercontent.com/81958811/127278005-e1f7b0b7-6aca-4861-9bdd-34e976dd3d21.jpg)




## Problem statement

Bob has started his own mobile company. He wants to give tough fight to big companies like Apple,Samsung etc.
He does not know how to estimate price of mobiles his company creates. In this competitive mobile phone market you cannot simply assume things. To solve this problem he collects sales data of mobile phones of various companies.
Bob wants to find out some relation between features of a mobile phone(eg:- RAM,Internal Memory etc) and its selling price. But he is not so good at Machine Learning. So he needs your help to solve this problem.

In this problem you do not have to predict actual price but a price range indicating how high the price is.

## Steps Involved:
* Importing Libraries
* Uploading dataset
* Analyze dataset
* Feature Selection
* Building model
* Training model and validating model
* Conclusion

## Libraries Required:
 
 Numpy
 Pandas
 Matplotlib
 Seaborn
 Scikit learn
 
## Dataset description
Data set can be downloaded by following https://www.kaggle.com/iabhishekofficial/mobile-price-classification  . The dataset contains information about many mobiles and variables about it.

## Attributes
1. battery_power: Total energy a battery can store in one time measured in mAh
2. blue: Has Bluetooth or not
3. clock_speed: the speed at which microprocessor executes instructions
4. dual_sim: Has dual sim support or not
5. fc: Front Camera megapixels
6. four_g: Has 4G or not
7. int_memory: Internal Memory in Gigabytes
8. m_dep: Mobile Depth in cm
9. mobile_wt: Weight of mobile phone
10. n_cores: Number of cores of the processor
11. pc: Primary Camera megapixels
12. px_height: Pixel Resolution Height
13. px_width: Pixel Resolution Width
14. ram: Random Access Memory in MegaBytes
15. sc_h: Screen Height of mobile in cm
16. sc_w: Screen Width of mobile in cm
17. talk_time: the longest time that a single battery charge will last when you are
18. three_g: Has 3G or not
19. touch_screen: Has touch screen or not
20. wifi: Has wifi or not
21. price_range: This is the target variable with a value of 0(low cost), 1(medium cost), 2(high cost) and 3(very high cost).

## Machine learning models:
* Logistic regression
* Naive Bayes
* K-NN
* Decision tree
* Random Forest
