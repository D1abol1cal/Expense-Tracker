# Flutter Expense Tracker

A simple Flutter app for logging day-to-day expenses, categorizing them, and visualizing spending per category with a bar chart.

![Flutter](https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?logo=dart&logoColor=white)

## Features

- **Add expenses** — title, amount, date and category, entered through a bottom-sheet form with input validation.
- **Categorization** — nine built-in categories (food, transportation, housing, utilities, health, personal, entertainment, education, clothing), each with its own icon.
- **Swipe to delete** — swipe an expense off the list to remove it, with an undo snackbar.
- **Spending chart** — a bar chart showing total spend per category.
- **Light & dark theme** — follows the system theme automatically.

Expenses are kept in memory for the current session and seeded with a few dummy entries on first launch; there's no persistence or sync yet.

## Getting started

```bash
git clone https://github.com/D1abol1cal/expense_tracker.git
cd expense_tracker
flutter pub get
flutter run
```

## Screenshots

<p>
  <img src="screenshots/WhatsApp Image 2024-03-23 at 4.11.37 PM.jpeg" width="200" />
  <img src="screenshots/WhatsApp Image 2024-03-23 at 4.11.38 PM.jpeg" width="200" />
  <img src="screenshots/WhatsApp Image 2024-03-23 at 4.11.38 PM (1).jpeg" width="200" />
  <img src="screenshots/WhatsApp Image 2024-03-23 at 4.11.39 PM.jpeg" width="200" />
</p>
