# Health-Compass

🩺 Health Compass - Final Web App
Submission Report
Project Overview
● Project Name: Health Compass
● Date: 06-06-
Project link :
https://drive.google.com/file/d/1hbHM0W4lS_GRWHJXekTPf6qf6uEhb0oQ/view?usp=sharing

App Summary
App Name: Health Compass User App
Platform: Web
Frontend Framework: Flutter Web
Flutter SDK Version: 3.32.
State Management: Getx
Architecture: Clean Architecture (Domain-driven, modular)

Authentication & Backend
The app integrates:
● Node.Js backend
● MongoDB for health data storage
● Firebase Hosting (for deployment)
If Firebase project access is needed, please share your Google email ID.

Project Structure
The project follows a clean and scalable folder structure:
├── core/ # Shared constants, utils, theme
├── data/ # Entities and repository contracts
├── routes/ # Navigation routes
├── services/ # services and data models
└── presentation/ # UI components, screens, and routing

Build & Run Instructions
Prerequisites:
● Flutter 3.32.0 installed
● Chrome or Edge browser
● Firebase CLI configured (firebase login and firebase init)
Setup:
Run flutter pub get
Run dart run build_runner build --delete-conflicting-outputs
Add Firebase credentials:
○ web/index.html must include Firebase config script.
○ .env file should include Firebase keys.
To Run:
flutter run -d chrome

To Deploy:
flutter build web
firebase deploy

Dependencies
Key packages used:
● getx– state management
● build_runner – data modeling
● firebase_auth, cloud_firestore, firebase_core, firebase_functions –
backend
● flutter_local_notifications – for notification support
● flutter_hooks, responsive_framework, intl – UI helpers

Testing
● Fully tested on latest versions of Chrome , Edge , and Firefox
● Responsive on mobile and tablet viewports
● Firebase connections verified with live data
● Form validations and error handling completed
Deliverables
● ✅ Source code folder (Google Drive link):
[Add your zipped project link here]
● ✅ Firebase project (pending access)
● ✅ This documentation
● ✅ Build (web/) folder if required
Final Notes
The Health Compass web app is ready for deployment and scaling. If you face any issue with
the Firebase setup or deployment process, feel free to reach out to us.

Submitted By:
Flutter Development Team, Logic Go Infotech LLP