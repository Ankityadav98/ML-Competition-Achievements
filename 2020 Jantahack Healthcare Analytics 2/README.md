# Jantahack-Healthcare-Analytics-II
## Problem Statement
Recent Covid-19 Pandemic has raised alarms over one of the most overlooked area to focus: Healthcare Management. While healthcare management has various use cases for using data science, patient length of stay is one critical parameter to observe and predict if one wants to improve the efficiency of the healthcare management in a hospital. 

This parameter helps hospitals to identify patients of high LOS risk (patients who will stay longer) at the time of admission. Once identified, patients with high LOS risk can have their treatment plan optimized to miminize LOS and lower the chance of staff/visitor infection. Also, prior knowledge of LOS can aid in logistics such as room and bed allocation planning.

Suppose you have been hired as Data Scientist of HealthMan – a not for profit organization dedicated to manage the functioning of Hospitals in a professional and optimal manner.
The task is to accurately predict the Length of Stay for each patient on case by case basis so that the Hospitals can use this information for optimal resource allocation and better functioning. The length of stay is divided into 11 different classes ranging from 0-10 days to more than 100 days.

[Link for the Dataset](https://datahack.analyticsvidhya.com/contest/janatahack-healthcare-analytics-ii/#ProblemStatement)

## Evaluation Metric
The evaluation metric for this hackathon is **100*Accuracy Score.**

## Algorithms Used
By using XGBoost on the dataset and tuning it by tweaking some hyperparamenters, i got **42.917% accuracy on public leaderboard with rank of 57.** The solution of the problem is contained in the file named 'XGBoost.ipynb'. I have also used Deep neural netwrok and LightGBM algorithms whose solutions are in the file named 'DNN.ipynb' and 'lightGBM.ipynb' respectively.

I got **42.74% accuracy on private leaderboard with a rank of 53.**

[Link to the Leaderboard](https://datahack.analyticsvidhya.com/contest/janatahack-healthcare-analytics-ii/#LeaderBoard)
