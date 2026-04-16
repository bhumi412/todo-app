# Todo App

## Project Description
This Todo App is a simple yet powerful application that allows users to manage their tasks efficiently. Users can add, edit, delete, and mark tasks as complete, providing a clear overview of their responsibilities and deadlines.

## Features
- **Add Tasks**: Users can create new tasks with a title and description.
- **Edit Tasks**: Existing tasks can be modified to update information as needed.
- **Delete Tasks**: Users can remove tasks they no longer need.
- **Complete Tasks**: Tasks can be marked as complete, providing a better overview of what has been achieved.
- **Local Storage**: All tasks are stored locally in the browser, ensuring data persistence even after refreshing the page.

## Installation Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/bhumi412/todo-app.git
   cd todo-app
   ```
2. Open `index.html` in your preferred web browser.

## Usage Guide
- To add a new task, enter the task title and description in the input fields and click 'Add'.
- Click on a task to edit it or use the delete icon to remove it.
- Mark tasks as complete by clicking the checkbox next to the task.

## Local Storage Explanation
This application uses the Web Storage API to store tasks locally in the user's browser. This means that even after closing or refreshing the browser, the tasks will remain available until explicitly cleared by the user. This is achieved using the `localStorage` object, which stores key-value pairs in a web browser.