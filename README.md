# AV-PerceptionModule

The **Robust Modelling of Deep Learning-Based Perception** project focuses on enhancing the reliability and robustness of perception modules in autonomous vehicles. The project addresses the challenge of inaccuracies and uncertainties in estimated distances obtained from learning-based algorithms, aiming to ensure the safety and effectiveness of autonomous vehicle behaviors.

## Table of Contents
- [Project Overview](#project-overview)
- [Problem Statement](#problem-statement)
- [Implemented Algorithms](#implemented-algorithms)
- [Project Achievements](#project-achievements)
- [Contributors](#contributors)

## Project Overview

The design of the Perception module is centered around vehicle-mounted RGB cameras, depth sensors, YOLO (You Only Look Once) object detection, and machine learning algorithms. By combining data from YOLO and depth sensors, the project aims to estimate the distance of obstacles or objects detected in front of the autonomous vehicle (referred to as 'ego'). These distance estimates are crucial for decision-making in autonomous vehicles.

## Problem Statement

The main challenge in this context is the potential unreliability of learning-based algorithms for distance estimation. If these algorithms produce inaccurate results, it can lead to unsafe behaviors of the autonomous vehicle. Therefore, the primary objective of this project is to design the Perception module in a way that mitigates the impact of inaccuracies and uncertainties in estimated distances on the overall decision-making process of the ego vehicle.

## Implemented Algorithms

To address these challenges, the following algorithms were implemented:

1. **Linear Regression**: A fundamental regression algorithm used to model the relationship between input data and estimated distances.

2. **Piece-Wise Linear Regression**: This approach divides the data into segments and fits separate linear regression models to each segment, allowing for more flexibility in modeling.

3. **Gaussian Process**: A probabilistic machine learning model that can capture complex relationships in the data and provide uncertainty estimates.

## Project Achievements

Through the implementation of these algorithms and related components, the project achieved significant milestones:

- **Improved Robustness**: The project's machine learning models increased the robustness of the perception module by 8%. This improvement enhances the reliability of distance estimation.

- **ETL Pipeline Integration**: The models were integrated into an ETL (Extract, Transform, Load) pipeline using Airflow, ensuring seamless data processing.

- **RESTful API Development**: A REST API was developed using Flask to provide easy access to the machine learning model outputs. This API enables real-time distance estimation.

- **Data Analysis with PowerBI**: PowerBI was employed for in-depth data analysis, generating actionable insights. These insights were instrumental in addressing failure modes and enhancing overall system performance.

- **CI/CD Pipeline**: A CI/CD (Continuous Integration/Continuous Deployment) pipeline was established using Jenkins. This pipeline significantly improved efficiency and automation in coursework grading, resulting in a 50% reduction in the course evaluation process.


## Contributors

- Rishi Patel (insert your contact information)

Feel free to reach out if you have any questions or would like to contribute to this project.

**Note**: This project is a work in progress, and contributions are welcome to further enhance the robustness of deep learning-based perception in autonomous vehicles.

---

*Disclaimer: This project is for research and educational purposes. It should not be used in production environments without appropriate validation and testing.*
