Overview

Mindscape is a web application designed to simplify mental health tracking through a user-friendly two-questions-a-day approach. The app integrates well-established psychological scales like the Perceived Stress Scale (PSS) and the Generalized Anxiety Disorder (GAD) scale to assess the user's mental health status. By answering just two daily questions, users can easily incorporate the app into their routine, making it an accessible tool for consistent mental health monitoring. Based on the responses, the app calculates PSS and GAD scores and generates personalized recommendations, offering tips and techniques for managing stress and anxiety.
Requirements
•Flutter SDK
•Firebase
•Visual Studio Code and Dart plugins 
Setup/Installation
1.Download and install the Flutter SDK from the official Flutter website.
2.Create a Firebase project at Firebase Console.
3.Enable Authentication, Realtime Database, and Cloud Functions in your Firebase project.
Configure Firebase in Flutter
   Add Firebase dependencies to pubspec.yaml.
   dependencies:
   firebase_core: latest_version
   firebase_auth: latest_version
   cloud_firestore: latest_version
   firebase_functions: latest_version
         use the command “flutter pub get”
Usage
Run the Application: ”flutter run”

Set Up Your Account
1.Open the Mindscape application on your device.
2.Register a new account by providing details such as name, email, and password.
3.Log in to your account to access the application's features.

Using the Application
1.Home Page:
View the homepage and navigate to different sections such as daily questions, stress level analysis, and recommendations.
2.Daily Questions:
Answer the daily questions based on the PSS and GAD scales to receive your mental health insights.
3.View Results:
Check your stress and anxiety levels, which are displayed with descriptive labels (Low, Moderate, High).
4.Recommendations:
The app generates recommendations using a rule-based algorithm that considers your PSS and GAD scores.
5.History and Analysis:
View a graphical representation of your stress and anxiety levels over time, helping you understand patterns and trends in your mental health.
This screen provides insights into how your mental health has changed over days, weeks, or months.

	
