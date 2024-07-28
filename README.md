# Fyle_health_challange_tracker
# Overview
Health Challenge Tracker is a single-page application (SPA) built with Angular 14+. This app enables users to log their workouts, manage workout data, and visualize their progress. Designed to assist users in maintaining their fitness goals, it offers an efficient way to monitor physical activities.

# Features
# User Input
Add User Details:Allows users to input their name, workout type, and workout duration.
Workout Tracking: Records and displays user workout data in a structured format.
# Workout List
#Search by Name: Quickly find users by searching their names.
Filter by Workout Type: Filter the workout list based on the type of workout.
Pagination: Efficiently navigate through a large list of users with pagination.
# Data Visualization
Workout Progress Charts: Optionally display users' workout progress using charts for better visualization.
Storage
LocalStorage: User data is stored locally using localStorage for persistence.
# Responsive Design
Responsive UI: The application is designed to be responsive and user-friendly, making it accessible on various devices.
# Screenshots

![Screenshot 2024-07-28 201959](https://github.com/user-attachments/assets/1c85014f-5b66-4290-b9ed-2a32009e17b6)
![Screenshot 2024-07-28 202914](https://github.com/user-attachments/assets/83f7aa3a-b086-4aff-a631-ef97a11a4006)
![Screenshot 2024-07-28 202829](https://github.com/user-attachments/assets/b10f7319-60f7-4fc8-afc7-961e1dbe018d)
![Screenshot 2024-07-28 202739](https://github.com/user-attachments/assets/ba94e20b-6c22-4766-b82c-e20253c53506)
![Screenshot 2024-07-28 202706](https://github.com/user-attachments/assets/99107a4e-6e3e-4e6c-97d8-dcb19f91e1d9)

# Getting Started
Follow these steps to run the application locally.

# Prerequisites
Node.js
Angular CLI
# Installation
# Clone the Repository:
git clone https://github.com/your-username/Health-Challenge-Tracker.git
# cd Health-Challenge-Tracker
# Install Dependencies:

npm install
Running the Application
# Start the Development Server:
ng serve
Navigate to http://localhost:4200/. The application will automatically reload if you change any of the source files.
# Code Scaffolding
To generate a new component, use the following command:

ng generate component component-name
# You can also use:

ng generate directive|pipe|service|class|guard|interface|enum|module
Building the Application
# To build the project, run:

ng build
The build artifacts will be stored in the dist/ directory.

Running Unit Tests
# To execute the unit tests via Karma, run:

ng test
or

npm run test
# To execute the unit tests with coverage, run:

npm run test:cov
Running End-to-End Tests
# To execute end-to-end tests via a platform of your choice, run:

ng e2e
Ensure to add a package that implements end-to-end testing capabilities first.
