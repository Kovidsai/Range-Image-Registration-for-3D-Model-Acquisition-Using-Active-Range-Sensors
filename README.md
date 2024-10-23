This project is part of My ComputerVision Course. 
In this project we tried to simulate Active 3d range sensors like LiDAR, ToF, ect in Blendor.
We used ".blend" files available online to conduct these experiments. 
Later we tried to register them (Also the data availble online) in a 3d mesh(environment) using multiplle variants of ICP algorithm.
Methodology:
First we preprocessed the data using RANSAC, DBSCAN depending on the nature of 3d object.
then registered these point clouds in 3d mesh using point to point, point to plane, coloured, Generalized ICP's Available in Open 3D Library.
Evaluated the results with RMSE and Fitting metrics.