An Android quiz tournament app built for ISCG7424 Assessment 2 (Semester 2, 2026). Admins create and manage quiz tournaments, and players take part in them.

## Install

1. Download `app-debug.apk` from this repository (or from the **Releases** page).
2. Copy it to an Android phone or emulator (Android 7.0 / API 24 or higher).
3. Open the file and allow installs from unknown sources if asked.
4. Open **Quiz App**. An internet connection is required.

## How to use

On the login screen, enter an email and a password (6 or more characters), choose **Player** or **Admin**, and tap **Register**. After that, use **Login**. To try both roles, register one account as each.

### Admin
- Create a tournament: name, category, difficulty, start date, end date, and rating (1 to 5)
- 10 questions are fetched from OpenTDB when a tournament is created
- View all tournaments with their status and ratings
- Edit a tournament's name, start date, and end date
- Delete a tournament (with confirmation)
- View the average player rating

### Player
- Browse Ongoing, Upcoming, Past, and Participated tournaments
- Play ongoing tournaments only, one question per screen, with feedback on each answer
- See the final score out of 10 and rate the quiz from 1 to 5

## Built with

- Java, Android Studio
- Firebase Authentication and Cloud Firestore
- Retrofit for the OpenTDB API (https://opentdb.com/)

- Java, Android Studio
- Firebase Authentication and Cloud Firestore
- Retrofit for the OpenTDB API (https://opentdb.com/)
