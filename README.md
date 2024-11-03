# Range Image registration for 3d model Acquisition using Active Range Sensors
This project is part of My ComputerVision Course. </br>
In this project we tried to simulate Active 3d range sensors like LiDAR, ToF, ect in Blendor. </br>
We used ".blend" files available online to conduct these experiments. </br>
Later we tried to register them (and Also the data availble online) in a 3d mesh(environment) using multiple variants of ICP algorithm. </br>
Methodology: </br>
First we preprocessed the data using RANSAC, DBSCAN depending on the nature of 3d object. </br>
then registered these point clouds in 3d mesh using point to point, point to plane, coloured, Generalized ICP's Available in Open 3D Library. </br>
Evaluated the results with RMSE and Fitting metrics. </br>
Code: [Colab Link] (https://colab.research.google.com/drive/1Rwr0kuZPVYTReYwnkIWjLblAMTbRMmiA#scrollTo=YYxZ30cWOWwP) </br>
Notes: We have used Jupyter Notebook for Visualizing 3D models and point clouds. (Colab doesn't support this. If you want any Alternative use Matplotlib) </br>
