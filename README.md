# OPSC7312_POE_Part2
Team CDJKY Part 2 Submission

Please note all code is under the "master" branch

This is a group submission, on behalf of Yuvaan Pather, Joshua Lester Reddy, Cian Luka Brink, Kayur Betchu, Dylan Pather

Repo Link:https://github.com/yuvi1126/OPSC7312_POE_Part2.git

YouTube Link:https://youtu.be/HIkE_HBAkBE


FitProPlus
FitProPlus is a comprehensive fitness tracking app designed to help users log workouts, track calories, engage with friends, and view leaderboards. The app aims to make fitness easier by providing user-friendly features that promote consistency and motivation.

Table of Contents
Introduction
How to Obtain the App
How to Run the App
How to Use the App
Logging Workouts
Tracking Calories
Friends and Leaderboards
Settings
App Features
Technologies Used

Introduction:

FitProPlus is a fitness app that allows users to monitor their workout routines, calorie intake, and progress over time. It includes a social element with friends and leaderboards, and users can personalize their experience with various settings. The app is available on Android devices and utilizes Firebase for user authentication and data storage.

How to Obtain the App

To obtain the FitProPlus app:

Download the APK file from the repository releases or from the designated app store (if available).
Alternatively, clone the repository and build the app using Android Studio (see instructions below).

How to Run the App

Requirements:
Android Studio 4.0+
Kotlin 1.4+
Firebase Project (you'll need to configure your Firebase credentials if running locally)
A working Android emulator or physical device for testing
Installation Steps:
Clone the repository to your local machine:git clone https://github.com/yuvi1126/OPSC7312_POE_Part2.git
Open the project in Android Studio.
Set up a Firebase project and add your google-services.json file to the app.
Enable Firebase Authentication (Email/Password) and set up Firestore Database in your Firebase console.
Build and run the app on an emulator or device:./gradlew build
Once the app is installed, you can create an account or log in if you already have one.

How to Use the App

Logging Workouts
Navigate to the Workout Plan section from the Home Screen.
Click Log Workout and fill in the details for your exercise (e.g., exercise name, sets, reps, and duration).
The workout will be saved, and you can view your progress over time in a graph.

Tracking Calories
Go to the Calorie Intake section to log meals and track your daily calorie intake.
Enter the food details and portion size. The app will calculate your consumed calories and show the remaining calories based on your maintenance goal.
View your calorie trends over the week in the graphical chart on the home screen.

Friends and Leaderboards
Click Friends on the home screen to see a list of other users who have accounts on the app.
Access Leaderboards to view a ranking of users based on the number of workouts logged.
Earn and view Trophies based on your workout achievements.

Settings
Access the Settings by clicking the profile icon on the home screen.
Modify your personal details (e.g., username, email), update your maintenance calories, or change the app language (Zulu, English, Afrikaans).
You can also reset your password if needed.

App Features
Workout Tracking: Log workout sessions with exercise name, sets, reps, and duration.
Calorie Tracking: Monitor daily calorie intake and compare against maintenance goals.
Visual Progress: View weekly progress through graphs for calories and workouts.
Friends and Social Engagement: Track friends' progress, compare workouts, and check leaderboards.
Trophies: Earn trophies based on achievements, including the number of workouts logged.
Customizable Settings: Change personal details, set maintenance calories, change language, and reset passwords.
Multi-language Support: Choose from Zulu, English, or Afrikaans.

Technologies Used
Kotlin: Primary programming language for the app.
Firebase Authentication: Handles user authentication and login.
Firebase Firestore: Used for storing user workout logs and data.
MPAndroidChart: Library used to generate the graphs for tracking calories and workouts.
GitHub Actions: Set up for automated testing and CI/CD.
Android Studio: IDE for building and running the Android app.




