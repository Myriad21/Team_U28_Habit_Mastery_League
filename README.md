# Habit Mastery League

## Overview
Habit Mastery League is a habit-tracking mobile application built with Flutter and Dart that helps users build and maintain consistent daily routines. The app is designed for students and individuals who want a simple and structured way to track habits such as studying, exercising, or personal development.

Users can create habits, mark daily completions, track streaks, and visualize their progress through heatmaps and statistics. The app also includes customizable settings such as dark mode, reminders, and motivational features to keep users engaged.

## Features
- Create, edit, and delete habits
- One-tap daily habit completion
- Streak tracking system
- Weekly completion heatmap visualization
- Statistics dashboard with trends and leaderboard
- Personalized insights and weekly reflection messages
- Habit buddy motivational messages
- Customizable settings (dark mode, notifications, reminder time, username)
- Data persistence across sessions

## Tech Stack
- **Framework:** Flutter
- **Language:** Dart
- **Database:** SQLite
- **Preferences Storage:** SharedPreferences
- **State Management:** setState

## Architecture / Project Structure
The app follows a layered architecture to separate concerns and improve maintainability:

- **UI Layer:** Screens and widgets (Dashboard, Add/Edit Habit, Details, Statistics, Settings)
- **Repository Layer:** Handles application logic and data flow between UI and database
- **Database Layer:** SQLite database storing habits and completion logs
- **Preferences Layer:** SharedPreferences for storing lightweight user settings

## How to Run the App
# Through APK
1. Locate the provided APK file in the project submission folder
2. Transfer the APK file to an Android device
3. Open the APK file on the device
4. If prompted, enable **Install from Unknown Sources** in device settings
5. Install the application
6. Open the app and begin using Habit Mastery League

## Alternative: Run via Emulator
1. Clone the repository: 
git clone https://github.com/Myriad21/Team_U28_Habit_Mastery_League

2. Navigate to the project folder: cd habit_mastery_league/lib


3. Install dependencies: flutter pub get


4. Start an emulator:

Eg. Android Studio


5. Run the app: flutter run


6. Ensure the emulator is running and selected as the target device.

**Note:** This app is designed for Android devices.

## How to Use the App
1. Launch the app and wait for the splash screen
2. On the dashboard, tap **Add Habit** to create a new habit
3. Enter details such as name, category, frequency, difficulty, and reminder time
4. Save the habit
5. Tap a habit on the dashboard to mark it complete for the day
6. Swipe a habit card to view details, edit, or delete it
7. Open the **Statistics** tab to view trends, streaks, and insights
8. Open the **Settings** tab to customize preferences like theme and notifications

## Data Storage
- Habit data is stored locally using SQLite
- Daily completion logs are stored in a separate table linked by a foreign key
- User preferences (username, theme, notifications, etc.) are stored using SharedPreferences
- All data persists locally across app sessions

## Team Roles
- **Trajuan Smith:** Database design, repository layer, and application logic
- **Raiyan Haque:** UI design, screens, and navigation

## Known Limitations / Future Improvements
- Add a full notification/reminder system
- Introduce advanced state management such as Provider for scalability
- Improve testing and validation for date-based features
- Optimize database queries for better performance
- Enhance UI polish and responsiveness

## Conclusion
This project demonstrates a full-stack mobile application built with a clean layered architecture. By combining Flutter for UI, SQLite for structured data, and SharedPreferences for settings, the app provides a scalable and user-focused solution for habit tracking and personal growth.