# Punch.In - A Strategic AI Attendance Planner
### Live Application: [punchin-tracker.vercel.app](https://punchin-tracker.vercel.app/index.html)

## About The Project
Punch.In is a smart, cloud-synced web application designed to help students move beyond simple attendance tracking and into strategic academic planning. It provides a comprehensive suite of tools to calculate attendance needs, manage subjects, and receive personalized, AI-powered advice on how to best manage their schedule.

This project was developed as a full-stack application, evolving from a simple concept to a secure, account-based platform with a real-time database and an integrated AI assistant.

## Core Features
* Cloud-Synced Accounts: User data (subjects, attendance, timetables) is tied to their personal account and synced across all devices using Firebase Authentication and Firestore.

* Comprehensive Attendance Calculator: Four distinct calculation modes to determine exactly how many classes a user needs to attend or can afford to miss to meet their goals.

* At-a-Glance Dashboard: A dynamic "Attendance Overview" provides an immediate visual summary of the user's standing in every subject.

* Customizable Timetable: A clean, intuitive interface for users to set their weekly class schedule, including the number of hours per subject on any given day.

* Strategic AI Bunk Planner: The flagship feature. By integrating the Gemini API with Google Search, the planner:

* Fetches real-time public holiday data for the user's location.

* Analyzes the user's attendance data and personal timetable.

* Generates strategic recommendations for the best days to miss class to achieve a long weekend.

* Provides an actionable plan on how to "earn" a day off if their attendance is currently too low.

## Tech Stack
This application was built using a modern, serverless architecture:

* Frontend: HTML, Tailwind CSS, JavaScript

* Backend & Database: Google Firebase (Firestore & Authentication)

* AI & Search: Google's Gemini API with Google Search grounding

* Deployment: Vercel

### A Note on Source Code
The source code for this project is maintained in a private repository. This public repository serves as a professional showcase of the application's features and technical architecture.

To see the application in action, please visit the live link above.
