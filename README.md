# food_recommendation_system_KNN
Based on a food recommendation system and food recommendation system-case base, the KNN system applied.
In this repo Euclidean distance is used to find the nearest neighbor
the number of neighbor is considered 3 
Considering that 6 types of features have been considered for the cases, the weighting method is as follows: 
for the eating place feature, the weight is 5, the state feature is weight 3, the event feature is weight 2, the activity feature is weight 3, and the meal status feature is It will have a weight of 2. The method based on the closest neighborhood, according to the value of 3, which is considered for it, looks for the closest values for the desired problem among the items stored in a database of cases.
The noteworthy point is that the implementation of the KNN method by applying different weights and using the Euclidean distance has the same result in comparison with the implementation of the case-based method using the Mahalanobis distance in the investigated cases. For example, the solution provided for both item-based and distance-based methods
Mahalanobis and KNN method using Euclidean distance for the following case are the same.
<img width="801" alt="Screen Shot 1402-01-04 at 17 30 09" src="https://user-images.githubusercontent.com/85408877/227541692-60e27098-4f14-4752-a372-79317d2c5c6a.png">
<img width="785" alt="Screen Shot 1402-01-04 at 17 30 20" src="https://user-images.githubusercontent.com/85408877/227541725-d206cf47-9aa6-4251-8830-8e1ef3057379.png">


The only difference in the two examined cases is in the events that happened during the day. He has participated in the  the book exhibition in database and participated in the piano recital for the new case reviewed.
