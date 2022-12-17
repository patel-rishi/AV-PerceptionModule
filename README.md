# AV-PerceptionModule
ECE-699 Project

The design of Perception module is based on vehicle mounted RGB camera, Depth sensors and YOLO and object detection module. With the help of YOLO+sensor we can get an estimate of the distance of any obstacle/object detected in front of the autonomous vehicle (also called ‘ego’). These distances are fed to learning based algorithms to give us an estimate of the actual distance. The main problem with such kind of learning-based algorithms is that they are unreliable, meaning the whole decision model can fail in case the algorithm gives inaccurate results, which can ultimately lead to unsafe ego behaviours. Hence, the main goal of the project is to design the Perception module in such a way that these inaccuracies and uncertainties in estimated distance, won’t affect the overall decision making of Ego’s behaviour. 

The following algorithms were implemented: Linear Regression, Piece-Wise linear regression and Gaussian Process