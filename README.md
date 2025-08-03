# Fitness-Tracking-Application
Mobile Activity Recognition App (Java, Android)
This project is a privacy-focused fitness tracking app developed in Java for Android. It uses an on-device machine learning model to recognize user activities (e.g., walking, jogging, sitting) based on accelerometer sensor data—removing the need for expensive wearables or cloud processing.

 Key Features
On-Device Machine Learning:
Activity classification performed locally using accelerometer data (collected at 20Hz in overlapping 5-second windows), ensuring data privacy and offline functionality.

Real-Time Data Pipeline:
Built an end-to-end pipeline in Java to:

Stream and preprocess sensor data

Extract relevant features

Classify activities with the deployed model

Store predictions in a local SQLite database via Room ORM

User Interface & Insights:

Real-time activity log with timestamps

Actionable fitness insights such as:

Total active/inactive time

Estimated calories burned

Insights update dynamically based on activity data and user profile changes

Architecture & Design:
Utilized Android Architecture Components (ViewModel, LiveData, Repository Pattern) for a robust, maintainable, and testable design.
Room ORM simplifies database access by mapping SQLite tables to Java objects.

📱 Tech Stack
Java

Android SDK

Room ORM

SQLite

MVVM Architecture

Machine Learning Model (integrated & deployed on-device)

