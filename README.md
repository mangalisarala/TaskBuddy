# 🌟 TaskBuddy App

<img width="1440" alt="Screenshot 2025-01-08 122734" src="https://github.com/user-attachments/assets/3a808ae0-0bdc-4d34-85b4-5f53ebe03dd4" />

TaskBuddy is a ReactJS-based task management application that helps users efficiently manage their tasks. The app supports adding, updating, and deleting tasks, with all data stored locally in the browser for persistent usage.

## ✨ Features

- **Add Tasks**: Users can add tasks to their task list.
- **Local Storage**: Tasks are stored in the browser's local storage for persistence.
- **Change Task Status**: Mark tasks as complete or incomplete with a single click.
- **Delete Individual Tasks**: Remove specific tasks from the list.
- **Clear All Tasks**: Remove all tasks at once (button is displayed only if there is at least one task).
- **Dynamic Buttons**: Each task has a "Complete" and "Delete" button for easy management.
- **Progress Tracker**: Visual representation of the task completion status.

## 🔧 How It Works

1. **Add Tasks**:
   - Enter a task in the input field and click the "Add Task" button.
   - The task is added to the list and stored in local storage.

2. **Mark as Complete**:
   - Click the "Complete" button to mark a task as completed.
   - Completed tasks are visually distinguished.

3. **Delete Tasks**:
   - Use the "Delete" button to remove a specific task from the list.

4. **Clear All Tasks**:
   - Click the "Clear All Tasks" button to remove all tasks.
   - The button is hidden if there are no tasks in the list.

5. **Progress Tracker**:
   - The app visually tracks task completion.
   - The progress tracker shows the percentage of completed tasks in the list, giving users a quick overview of how much of their task list has been completed.
   - This percentage is dynamically updated whenever a task is marked as complete or incomplete.
   - The tracker is displayed at the top of the task list for easy access.

## 🛠️ Technologies Used

- **ReactJS**: For building the user interface.
- **Local Storage**: To store tasks persistently in the browser.
- **CSS**: For styling the application.

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/taskbuddy-app.git
