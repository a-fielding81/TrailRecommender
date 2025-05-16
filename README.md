# Trail Recommendation System Notebook Project

## Introduction

This repo includes the files necessary to explore a national park trail recommendation system I built based on KNN matching and K means clustering using scikit learn. 

The idea for the project was inspired by a trip I had recently taken to Yosemite National Park, where my family had only two days to try to see and do everything we wanted to do in the park. Solutions like AllTrails existed to help you search for trails, but we were unfamiliar with Yosemite and I thought it would have been helpful to have a tool that could actually recommend specific trails based on our preferences, rather than just returning large lists of trails based on a few filters. I therefore implemented this project with a group to submit as our final work for Northeastern's DS2500 class. The project relies on K Nearest Neighbors and K Means Clustering to make its recommendations, and it incorporates a basic scaling algorithm to allow a user to weight certain trail features more heavily than others.

You are free to copy, modify, distribute, and otherwise use the project for any purpose. Please feel free to contact me at afielding2025@gmail.com with questions, concerns, bugs, issues, or suggestions. 

## Use of the recommendation system

This notebook is a full data analysis that is meant to be run from top to bottom. If you would like to see the same outputs that were used to generate the analysis at the bottom, be sure to examine the stored outputs before clearing them so you can recreate those we used for our examples. Otherwise, feel free to use your own input preferences to get tailored recommendations. Just be advised that the portions of the notebook that analyze our specific examples will no longer be relevant. 

Additionally, it is critical to run all data cleaning cells at the top of the notebook. However, note that the cell that creates the csv file avg_park_dataset.csv can be redundant, as the project is saved to GitHub with that file already created. Therefore, running that cell may be unnecessary, even if it should not cause any issues. Future work on this project likely would have involved splitting the data cleaning and file creation functions out of the main notebook and into separate files for better organization.

## Notes

This project was completed three years ago and uploaded to GitHub in May, 2025. The code has been updated to work with the latest versions of libraries like Pandas (2.2.3) and SciKit Learn (1.6.1), but there may be still be issues with dependencies and deprecated features. Please contact me if any arise. Additionally, this project was for an introductory data science class. It earned top marks and performed to the professor's standards, but its methodologies may be flawed and it is not meant for production deployment. Please double check results and think critically about outputs, and/or contact me with questions or issues. 

## Acknowledgements

I am grateful for the work of my 3 teammates and the assistance of our professor. I will not share their names out of respect for their privacy, but they each made invaluable contributions to this project. 