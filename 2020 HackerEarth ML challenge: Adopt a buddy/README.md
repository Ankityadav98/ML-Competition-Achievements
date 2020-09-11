# Problem Statement
Numerous organizations across the world provide shelter to all homeless animals until they are adopted into a new home. However, finding a loving family for them can be a daunting task at times. This International Homeless Animals Day, we present a Machine Learning challenge to you: Adopt a buddy.

The brighter side of the pandemic is an increase in animal adoption and fostering. To ensure that their customers stay indoors, a leading pet adoption agency plans on creating a virtual-tour experience, showcasing all animals available in their shelter. To enable that, you have been tasked to build a Machine Learning model that determines type and breed of the animal based on its physical attributes and other factors.

# Dataset
The dataset consists of parameters such as: a unique ID assigned to each animal that is up for adoption, date on which they arrived at the shelter, their physical attributes such as color, length and height, among other factors.


# Evaluation Metrics
s1=f1_score(actual_values[′pet_category′],predicted_values[′pet_category′],average=′weighted′)
s2=f1_score(actual_values[′breed_category′],predicted_values[′breed_category′],average=′weighted′)

score=100×(s1+s2)/2

**Private Leaderboard Rank:** 108 ([Link to the Leaderboard.](https://www.hackerearth.com/challenges/competitive/hackerearth-machine-learning-challenge-pet-adoption/leaderboard/pet-adoption-9-5838c75b/page/3/))
