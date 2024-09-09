# To-Do-List


## Overview
This is a simple and efficient **To-Do List Web Application** that allows users to manage their tasks efficiently. The app provides functionality to create, edit, delete, and mark tasks as completed. It also includes  login/logout functionality, search features, and data persistence using the browser’s **localStorage**.
## View here  
## Features
- **Login & Logout System**: Users can log in to access the app and securely log out. User credentials are saved in the browser's local storage.
- **Add Tasks**: Users can add new tasks with just a simple input.
- **Edit Tasks**: Edit existing tasks.
- **Delete Tasks**: Remove tasks from the list when they are no longer needed.
- **Mark as Complete**: Mark tasks as done, visually differentiating between completed and pending tasks.
- **Search Tasks**: Users can search for tasks using the search bar, dynamically filtering tasks.
- **Persistent Data**: Tasks and login status are saved in the browser's local storage, ensuring tasks are available even after closing and reopening the browser.

## Technologies Used
- **HTML**: Structure of the web application.
- **CSS**: Styling and layout for a responsive user interface.
- **JavaScript**: Core functionality and logic for managing tasks, authentication, and interaction.
- **LocalStorage API**: Storing user tasks and login data locally, ensuring persistence across browser sessions.
- **JSON**: Used for storing and retrieving task data from localStorage.

## How It Works

### Login 
- Users input their credentials (username and password).

- Upon logout, the user’s session is cleared.

### Task Management
- Users can create tasks by filling out a simple input form.
- Tasks can be edited or deleted as required.
- Mark tasks as completed by checking the task box. Completed tasks are visually distinguished.
- Tasks are stored in localStorage in JSON format, ensuring data persistence.

### Search Functionality
- Users can search for tasks using the search bar. As users type, the task list is dynamically filtered to show only the relevant tasks.

### Overlay for Adding Tasks
- The app uses an overlay form that pops up when adding new tasks, ensuring an interactive and engaging user experience.

### Logout
- The **logout** function clears the user’s session , local storage and returns them to the login page.

## Challenges Faced
1. **Persisting Data Across Sessions**: Using **localStorage** to store tasks and user credentials was key to ensuring that data remains available even after the page is refreshed or the browser is closed.
2. **Dynamic Task Filtering**: Implementing real-time search required efficient filtering of the task list without performance degradation.

## Improvements for the Future
- **Backend Authentication**: Implement a secure authentication system using a backend (e.g., Node.js, Python) and database (e.g., MongoDB) for secure user data management.
- **Task Prioritization**: Add categories or priority levels for each task, allowing users to better manage tasks based on importance.
- **Real-time Collaboration**: Extend the app to allow multiple users to collaborate and share tasks, using **WebSockets** or **Firebase** for real-time updates.
- **Advanced Search**: Enhance the search functionality with advanced filters such as by due date, task completion status, or priority level.

## Set Up

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/todo-list-app.git

2. **Run the application**:

   Open the index.html file in your browser to view the to-do list app.
