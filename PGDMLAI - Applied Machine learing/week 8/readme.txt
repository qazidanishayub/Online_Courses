Clustering
Author: Jessica Cervi

Expected time = 2.5 hours

Total points = 60 points

Assignment Overview
In this assignment, we will work on clustering algorithms.

In general, the steps of clustering algorithms are straightforward:

The sample points are assigned to centroids
The coordinate of the centroid gets updated
These two main steps repeat until we get convergence in our algorithm. When using clustering, some of the difficult steps are:

How to select the number of centroids required?
How to initialize the selected centroids?
Although these are important topics in clustering, in this assignment, we will focus on the main steps that define the clustering algorithm. In particular, you will be asked to write functions that compute k-means, soft k-means, and GMM clustering. Like all the other previous assignments, the pre-built versions in the sklearn of these algorithms will be demonstrated at the end of the lesson.

This assignment is designed to build your familiarity and comfort in coding in Python. It will also help you review the key topics from each module. As you progress through the assignment, answers to the questions will get increasingly complex. You must adopt a data scientist's mindset when completing this assignment. Remember to run your code from each cell before submitting your assignment. Running your code beforehand will notify you of errors and giving you a chance to fix your errors before submitting it. You should view your Vocareum submission as if you are delivering a final project to your manager or client.

Vocareum Tips

Do not add arguments or options to functions unless asked specifically. This will cause an error in Vocareum.
Do not use a library unless you are explicitly asked in the question.
You can download the Grading Report after submitting the assignment. It will include the feedback and hints on incorrect questions.
Learning Objectives
Determine the distance from data through cluster centers
Assign cluster values using soft/hard clusters
Assign cluster values using Gaussian distributions
Update cluster centers using hard/soft/gaussian mixture clustering
Implement Gaussian mixture models and k-means clustering using 'sklearn'