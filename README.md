# To-Do List App

A Flutter To-Do List application that allows users to add, complete, delete, and persist tasks locally using SharedPreferences.  
The app features a clean UI and ensures tasks remain saved even after the app is closed.

Features:
- Add new tasks
- Mark tasks as completed
- Delete individual tasks
- Clear all tasks at once
- Persistent local storage using SharedPreferences
- Clean and responsive UI
- Task completion with strike-through effect

Technologies Used:
- Flutter
- Dart
- SharedPreferences
- JSON Encoding/Decoding
- Material Design Widgets
- StatefulWidget

Local Storage:
Tasks are stored locally using SharedPreferences.  
Data is encoded into JSON format and saved on the device, ensuring persistence even after restarting the app.

How It Works:
- User enters a task in the input field.
- Task is stored in a List of Map objects.
- Data is converted to JSON and saved using SharedPreferences.
- On app start, saved tasks are loaded and displayed.
- Users can:
  - Toggle completion status
  - Delete specific tasks
  - Clear all tasks

Author:
Mohini Santosh Malap

GitHub: https://github.com/yourusername


1. Clone the repository  
