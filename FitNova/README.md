# FitNova

FitNova is a native Android fitness tracker app for CodeAlpha Task 3.

## Main Features

- Splash screen with FitNova logo
- Signup and login flow
- Local session management
- Light mode professional dashboard
- Custom bottom navigation with controlled icon and text spacing
- Notification bell with daily reminders and progress alerts
- Clean profile screen with account options
- Manual activity logging
- Exercise type dropdown selector
- Exercise type, date, workout minutes, steps, calories and water cups
- SQLite offline storage
- Daily summary dashboard
- Weekly step progress chart
- Activity history with delete and clear all options
- Editable daily fitness goals from Profile

## How To Open

1. Open Android Studio.
2. Select "Open".
3. Choose the `FitNova` folder.
4. Let Gradle sync.
5. Run the app on an emulator or Android phone.

## Important Files

- `app/src/main/java/com/example/fitnova/MainActivity.java`
  Main UI and screen navigation.

- `app/src/main/java/com/example/fitnova/SplashActivity.java`
  Splash screen and login-session routing.

- `app/src/main/java/com/example/fitnova/AuthActivity.java`
  Signup and login flow.

- `app/src/main/java/com/example/fitnova/FitnessDbHelper.java`
  SQLite database logic.

- `app/src/main/java/com/example/fitnova/FitnessEntry.java`
  Fitness log model.

- `app/src/main/java/com/example/fitnova/DailySummary.java`
  Daily summary model.

- `app/src/main/res/layout/activity_main.xml`
  Main app shell with custom bottom navigation container.

- `app/src/main/res/menu/bottom_nav_menu.xml`
  Home, Log, Progress, History and Profile tabs.

- `app/src/main/res/values/colors.xml`
  FitNova color palette.

- `app/src/main/res/values/styles.xml`
  Light theme and navigation active indicator style.

- `app/src/main/res/drawable/ic_launcher.xml`
  FitNova app logo.

- `gradle.properties`
  Enables AndroidX support for AppCompat and Material components.
