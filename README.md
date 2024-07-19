# E-Learning Student Dataset
## Overview
This dataset contains information about students' interactions with e-learning courses. 
It includes details such as session durations, course completion status, user satisfaction, and feedback. 
This data can be used to analyze student engagement and performance in online learning environments.

## Data Description
The dataset includes the following columns:

1. UserID: Unique identifier for each user.
2. CourseName: Name of the course the user is enrolled in.
3. SessionDuration: Duration of each session in minutes.
4. SessionsPerWeek: Number of sessions attended per week.
5. CourseCompletion: Binary indicator of whether the course was completed (0 for not completed, 1 for completed).
6. UserSatisfaction: Satisfaction score given by the user, typically on a scale (e.g., 1 to 5).
7. SignUpDate: Date when the user signed up for the course (formatted as DD-MM-YYYY).
8. LastActiveDate: Date when the user was last active on the course (formatted as DD-MM-YYYY).
9. QuizScores: Scores obtained by the user in quizzes, as a percentage.
10. FeedbackComments: User's comments or feedback regarding the course.

## Learning outcomes
This dataset can be utilized for various types of analyses:
Supervised Learning:
Predicting CourseCompletion based on features such as SessionDuration, SessionsPerWeek, UserSatisfaction, and QuizScores.
Predicting UserSatisfaction based on features like SessionDuration, SessionsPerWeek, and QuizScores.
Unsupervised Learning:
Clustering users based on their engagement metrics (SessionDuration, SessionsPerWeek, QuizScores) to identify patterns or segments.
Analyzing FeedbackComments to extract common themes or sentiments.

## Data Source
The dataset was sourced from kaggle.

