# Human-Activity-Recognition-HAR-
The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data. 
In this project, I used 2 different types of ML algorithms with different parameters and compare the accuarcy among those models, I used KNN means with different number of neighbors and compare the model when using PCA and not using it. 
The second model I used it XGBoost Classifier that gave a really low accuarcy.
Finally I used Neural Networks especifically MLP. I ran the model 1 or 2 hidden layers, and 2 activation methods (relu, and tahn), and different number of nodes in each layer. Finally, compared the accuarcy of each MLP model's accuarcy and looses.

The data was obtained from the next paper:
Davide Anguita, Alessandro Ghio, Luca Oneto, Xavier Parra and Jorge L. Reyes-Ortiz. A Public Domain Dataset for Human Activity Recognition Using Smartphones. 21th European Symposium on Artificial Neural Networks, Computational Intelligence and Machine Learning, ESANN 2013. Bruges, Belgium 24-26 April 2013. 

This dataset is distributed AS-IS and no responsibility implied or explicit can be addressed to the authors or their institutions for its use or misuse. Any commercial use is prohibited.
