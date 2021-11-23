# Titanic Machine Learning from Disaster

Created the Machine the Learning model on Kaggle Titanic Dataset. I have tried many different algorithm (like GradientBoostingClassifier, KNN, Catboost, etc.), to find which algorithm perform the best. Following are the accuracy scores on different algorithms:

![Screenshot (153)](https://user-images.githubusercontent.com/80076688/142956961-67c389d7-f262-4d16-a919-deac88f087e5.png)


However, We can't judge the model's accuracy on a single validation, so I have tried range of different Cross Validation on different algorithm. Here is the socres:

![Screenshot (155)](https://user-images.githubusercontent.com/80076688/142957061-e63793d0-9501-4ef1-b935-ed3aeb7f7666.png)

According to this image the GradientBoostingClassifier is works well, but on this algorithm the total 50 Cross validation I have applied, and on CatBoost I have applied just 10 Cross Validation. 

Hence, at the end I have decieded to use CatBoost algoritm, and interestingly, the model's prediction was 80.78%. (https://www.kaggle.com/parth7878/competitions)
