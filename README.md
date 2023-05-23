![image](https://github.com/josiah-okumu/phase-3-project/assets/125944738/66d08945-aa4b-4832-8890-1e29971e523f)

# Overview
My client is the Vehicle Safety Board, interested in reducing the accident cases in the city of Chicago. The board is looking into helping the car manufacturers and buyers to equally feel safer on the roads. This software would be used to identify the leading causes of death in the city of Chicago and save the lives of the car occupants, including the driver. The software would be able to recognize the prevailing situation at the time of accidents and compares it with the previous crashes, notifying the board of a possible fatality on a specific area. the classification model created in this case will predict the prime factors causing an accident and whether the accident is fatal. If successfully implemented by the Vehicle Safety Board, they will raise awareness to the road users within the city on the possible causes of death, how to evade them to reduce fatality risks and improve safety of the road users.
# Business and Data Understanding
My client, Vehicle Safety Board wants to know hoe they can identify and reduce crashes that happens within the city. This will inform their cause of action based on the outcome of the major causes of accidents and how fatal they are. The board seeks to know to prevent the fatal crashes on the roads, so that it does a recommendation to the government on ways of reducing the crashes that happens within the city of Chicago.

My stakeholder, the Vehicle Safety Board is set to launch campaign that is aimed at reducing car crashes along the roads. The task in this case is to build a classification model to identify the major causes of car crashes and how to prevent the fatalities of these crashes when they happen, group them as preventable or non-preventable, based on the monetary implication involved in abating the cause of the crash.
# Objectives

* To provide inferential statistics and visualisations based on this data.
* To build a classification predictive and supervised learning models from the data to predict causes of crash and how to prevent crashes on the roads

# Database
The dataset that was used for these purpose a realtime data that is recorded and released by the different police departments within the city of Chicago. I used three datasets;Traffic Crashes- Crashes, Traffic Crashes-People and Traffic Crashes-Vehicle, whose sources are as follows:

Crashes: https://data.cityofchicago.org/Transportation/Traffic-Crashes-Crashes/85ca-t3if

Vehicle: https://data.cityofchicago.org/Transportation/Traffic-Crashes-Vehicles/68nd-jvt3

People: https://data.cityofchicago.org/Transportation/Traffic-Crashes-People/u6pd-qa9d

# Exploratory Data Analysis
Creating visualizations to understand better the data for the features selected for analysis;

![image](https://github.com/josiah-okumu/phase-3-project/assets/125944738/438f7475-caf3-4d9a-96ed-a6f2fb09b15e)


# Modelling
* Dummy Classifier
* Decision Tree
Dummy classifier was used as the baseline model to make predictions based on the causes of crash in the city of Chicago. In order to evaluate this model, decision tree was used nd the two nearly gave the same accuracy, meaning none of them was perfect over the other.

# Evaluation



# Conclusion

Since both the baseline model and the decision tree compared have nearly the same accuracy/best score values, means that the decision tree is not providing any better results, hence not an improvement to the previous baseline predictive model. Further, looking at the complexity of the decision tree model and its interpretation since it has got many stems. this makes the decision tree not to be a choice of the improvement model over the previous baseline model as it tends to be more heavily loaded in terms of data and interpretation as the baseline model.
