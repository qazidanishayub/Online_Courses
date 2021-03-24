Recommender Systems
Author: Carleton Smith

Reviewer: Jessica Cervi

Expected time = 2.5 hours

Total points = 90 points

Assignment Overview
In this assignment, we will work on recommender systems. Recommender systems provide a non-parametric comparison between items. They are fundamental in analyzing how individuals can be served. This project consists of 4 parts:

General Familiarization with the data.
Mathematical foundations of recommender systems and simple examples about them.
Execution of methods on the data.
Short introduction to the Surprise package.
All the methods used below should be familiar from the material from this week's lectures. Except for the singular value decomposition (SVD) and the Surprise package, we will review some main concepts before demonstration.

The general goal of this project is, given a collection of users, items, and user reviews of the items, predict what score a user would assign to an item they have yet to review.

We will be working with a synthetic review dataset, modeled on reviews from Amazon. To demonstrate the techniques, in all our examples, we will work only with a smaller portion of the made-up data.

This assignment is designed to build your familiarity and comfort in coding in Python. It will also help you review the key topics from each module. As you progress through the assignment, answers to the questions will get increasingly complex. You must adopt a data scientist's mindset when completing this assignment. Remember to run your code from each cell before submitting your assignment. Running your code beforehand will notify you of errors and giving you a chance to fix your errors before submitting it. You should view your Vocareum submission as if you are delivering a final project to your manager or client.

Vocareum Tips

Do not add arguments or options to functions unless asked specifically. This will cause an error in Vocareum.
Do not use a library unless you are explicitly asked in the question.
You can download the Grading Report after submitting the assignment. It will include the feedback and hints on incorrect questions.
Learning Objectives
Understand mathematical foundations of recommender systems
Translate a mathematical algorithm into code
Determine similarity between items by using Euclidean distance, Pearson's coorelation-coefficient, and cosine similiarty
Predict item recommendations using similarity scores
Understand utilization complexity to noramlize user ratings
Make item recommendations using singular value decomposition (SVD)
Implement SVD using the surprise package