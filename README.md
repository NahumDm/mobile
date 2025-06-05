# Simple Task Manager

A clean and intuitive Flutter-based task management application that helps users organize their daily tasks efficiently.

## Features

- **Task Management**

  - Add new tasks with a simple input field
  - Mark tasks as completed/uncompleted
  - Delete tasks
  - View all tasks in a scrollable list
  - Visual indication of completed tasks (strikethrough text)

- **User Interface**
  - Clean and modern Material Design
  - Responsive layout
  - Intuitive task input system
  - Easy-to-use task controls

## Technical Details

### Tools & Technologies

- **Framework**: Flutter
- **Language**: Dart
- **State Management**: Local State Management using `setState`
- **UI Components**: Material Design widgets

### Key Components

1. **Task Model**

   ```dart
   class Task {
     String title;
     bool isCompleted;
   }
   ```

2. **Main Features Implementation**
   - Task creation with validation
   - Task completion toggle
   - Task deletion
   - Task list filtering

### Widget Structure

- `MaterialApp`: Root widget with app configuration
- `TaskManagerPage`: Main screen widget
- `TextField`: Task input field
- `ListView.builder`: Efficient task list rendering
- `ListTile`: Individual task item display

## Getting Started

1. Ensure you have Flutter installed on your system
2. Clone this repository
3. Run `flutter pub get` to install dependencies
4. Run `flutter run` to start the application

## Usage

1. **Adding a Task**

   - Type task description in the input field
   - Press Enter or tap the add button
   - Empty tasks are automatically prevented

2. **Managing Tasks**
   - Tap checkbox to mark task as complete
   - Tap delete icon to remove a task
   - Completed tasks show strikethrough text

## Best Practices Implemented

- Proper resource management with `dispose()`
- Input validation
- Efficient list rendering
- Clean code structure
- Memory leak prevention

## Future Enhancements

Potential features that could be added:

- Task categories
- Due dates
- Priority levels
- Data persistence
- Search functionality
- Task sorting options
