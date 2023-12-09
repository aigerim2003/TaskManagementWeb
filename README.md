# TaskManagementWeb
Task Addition:

The code adds a new task when the user clicks the "Add Task" button.
It creates a new list item (<li>) containing an input field for the task, delete button, and edit button.
The new task is appended to the task list (<ul>).
Task Deletion:

If the user clicks the "Delete" button of a task, the corresponding list item is removed.
Task Editing:

If the user clicks the "Edit" button of a task, it toggles the disabled state of the task's input field.
Clear All Tasks:

Clicking the "Clear All Tasks" button removes all tasks from the task list.
Task Searching:

The code filters tasks based on the user's input in the search bar.
User Authentication (main.js):
Login Form:
It handles the login form, preventing its default submission and displaying an error message for an invalid username/password combination.
User Authentication (login.js):
Form Switching:

It allows switching between the login and create account forms when clicking the respective links.
Signup Username Validation:

It validates the length of the signup username and displays an error message if it's less than 10 characters.
Input Event Listeners:

It includes event listeners for input blur and input events to handle input errors.
