# FitArc — Screen List

## 1. Splash Screen
- Displays the FitArc app identity.
- Introduces the app before the login screen.

## 2. Login Screen
- Provides a demo login interface.
- Allows navigation to the home dashboard.
- Does not use real authentication.

## 3. Home Dashboard
- Displays a welcome header.
- Shows workout progress.
- Highlights a featured workout.
- Displays recent workouts.
- Provides bottom navigation.

## 4. Workout Library
- Displays available workout records.
- Provides a search field and category filters.
- Allows users to open workout details.
- Provides an option to add a workout.

## 5. Add Workout Screen
- Accepts workout name and category.
- Accepts exercise name, sets, reps, and duration.
- Provides a Save Workout action.
- Supports the planned add/edit form.

## 6. Workout Details Screen
- Displays the selected workout's information.
- Provides options to edit or delete a workout.
- Supports marking a workout as completed.

## 7. Account Screen
- Displays profile information.
- Provides appearance settings for light and dark themes.
- Includes notification settings and a demo logout action.

## Navigation
- Splash → Login
- Login → Home Dashboard
- Home Dashboard → Workout Library or Account
- Workout Library → Workout Details or Add Workout
- Workout Details → Edit Workout or Home Dashboard
- Account → Home Dashboard or Workout Library

## Design Notes
- Frame size: 390 × 844
- Font: Inter
- Accent color: #B7F36B
- Dark background: #101512
- Light background: #F5F7F4
- Dark surface: #252D28

**Note:** These screens and navigation flows are currently part of the Figma design prototype. They will be implemented in Flutter during Week 2.
