# To-Do App
A simple, interactive to-do list application built using HTML, CSS, and JavaScript. This app enables users to add, edit, and delete tasks, helping them stay organized and manage their daily tasks efficiently.

## Features
- Add New Tasks: Easily add tasks to your to-do list.
- Edit Tasks: Modify tasks as needed.
- Delete Tasks: Remove tasks that are completed or no longer needed.
- Mark Tasks as Completed: Track task progress by marking tasks as done.
- Persistent Data: Saves tasks in local storage so that they are available even after refreshing the page.
## Technologies Used
- HTML: Provides the structure for the app.
- CSS: Handles the styling and layout of the app.
- JavaScript: Implements the main functionality, including task management and data handling.
## Functionality
## Local Storage
- The app uses the browser’s local storage to save the task list. Local storage allows data to persist even after the page is refreshed, making it ideal for storing user data like to-do lists.
## Task Management
- Adding Tasks: When a user enters a new task and submits it, JavaScript captures the input and adds it to the list. This triggers a re-render of the task list with the new task.
- Editing Tasks: The app allows users to modify task text. When the edit button is clicked, JavaScript replaces the task text with an input field to update the content. Upon submitting, the task text is updated.
- Deleting Tasks: Users can remove tasks by clicking the delete button. JavaScript removes the item from both the display and local storage.
- Marking as Completed: A checkbox or line-through effect lets users visually mark tasks as completed.
