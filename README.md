# Head-Pose-Estimation

At the end of the supervised machine learning course at ITI we have worked on Head Pose Estimator  project , the problem in this project is that we do not have the Z-Axis of the landmarks of the face . only the X and Y, so we have used machine learning to solve this problem and draw the three axes the face rotates around them using pitch , yaw and roll angles.

through this project I have worked with my hard worker friend kerolos Yacoub to find a solution for this problem through those steps :

1-getting the dataset and extracting the features which are the x,y axis of each landmark of the face  and labels which are the yaw , pitch and roll for each image
2- Normalizing the features
3- performing hyper parameter tuning using Grid search for the SVR model
4-getting the results and testing it on an image and a video

