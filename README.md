# <b>Ambreen_DS_portfolio</b>
Data Science portfolio

# [Project-1: E-News-project webpage A/B testing](https://github.com/AmbreenBokhari/E-News-project/blob/main/E-news-xpress-new.ipynb)

An online news portal aims to expand its business by acquiring new subscribers. Every visitor to the website takes certain actions based on their interest. The company plans to analyze these interests and wants to determine whether a new feature will be effective or not. Companies often analyze users' responses to two variants of a product to decide which of the two variants is more effective. This experimental technique is known as a/b testing that is used to determine whether a new feature attracts users based on a chosen metric.
The design team of the company has created a new landing page. The task is to decide whether the new landing page is more effective to gather new subscribers. Suppose you randomly selected 100 users and divided them equally into two groups. The old landing page is served to the first group (control group) and the new landing page is served to the second group (treatment group). Various data about the customers in both groups are collected in 'abtest.csv'. Statistical analysis was performed to answer different questions using the collected data.



# [Project-2 ReCell-Data preprocessing and linear regression](https://github.com/AmbreenBokhari/ReCell-project/blob/main/Recell.ipynb)
Buying and selling used smartphones used to be something that happened on a handful of online marketplace sites. But the used and refurbished phone market has grown considerably over the past decade, and a new IDC (International Data Corporation) forecast predicts that the used phone market would be worth $52.7bn by 2023 with a compound annual growth rate (CAGR) of 13.6% from 2018 to 2023. This growth can be attributed to an uptick in demand for used smartphones that offer considerable savings compared with new models. Refurbished and used devices continue to provide cost-effective alternatives to both consumers and businesses that are looking to save money when purchasing a smartphone. There are plenty of other benefits associated with the used smartphone market.


# [Project-3 Cardio-good-fitness Exploratory Data Analysis using python](https://github.com/AmbreenBokhari/Cardio-good-fitness/blob/main/cardioproject-Copy1.ipynb)
The data is for customers of the treadmill product(s) of a retail store called Cardio Good Fitness. Task is to Explore the dataset to identify differences between customers of each product. Explore relationships between the different attributes of customers. It can be approached from any other line of questioning that seems to be relevant for the business.

# [Project-4 ReneWind Product Maintenance and Faliure Prediction Model](https://github.com/AmbreenBokhari/ReneWind-maintenance/blob/main/ReneWind-Project.ipynb)
“ReneWind” is a company working on improving the machinery/processes involved in the production of wind energy using machine learning and has collected data of generator failure of wind turbines using sensors. They have shared a ciphered version of the data, as the data collected through sensors is confidential (the type of data collected varies with companies). Data has 40 predictors, 40000 observations in the training set and 10000 in the test set.

The objective is to build various classification models, tune them and find the best one that will help identify failures so that the generator could be repaired before failing/breaking and the overall maintenance cost of the generators can be brought down.

“1” in the target variables should be considered as “failure” and “0” will represent “No failure”.

The nature of predictions made by the classification model will translate as follows:

True positives (TP) are failures correctly predicted by the model.
False negatives (FN) are real failures in a wind turbine where there is no detection by model.
False positives (FP) are detections in a wind turbine where there is no failure.
So, the maintenance cost associated with the model would be:

Maintenance cost = TP*(Repair cost) + FN*(Replacement cost) + FP*(Inspection cost) where,
Replacement cost = $40,000
Repair cost = $15,000
Inspection cost = $5,000
Here the objective is to reduce the maintenance cost so, we want a metric that could reduce the maintenance cost.
The minimum possible maintenance cost = Actual failures*(Repair cost) = (TP + FN)*(Repair cost)
The maintenance cost associated with model = TP*(Repair cost) + FN*(Replacement cost) + FP*(Inspection cost)
So, we will try to maximize the ratio of minimum possible maintenance cost and the maintenance cost associated with the model.
The value of this ratio will lie between 0 and 1, the ratio will be 1 only when the maintenance cost associated with the model will be equal to the minimum possible maintenance cost.
