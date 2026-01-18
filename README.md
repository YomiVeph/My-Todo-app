ToDo App

A simple yet powerful ToDo List web application to manage your daily tasks with priority levels, filtering options, and dark/light mode support. Tasks are saved in the browser using localStorage, so your tasks persist even after closing the browser.

Features

Add Tasks: Create new tasks with a title and assign a priority (Low, Medium, High).

Edit Tasks: Modify task titles inline by clicking on them.

Mark as Completed: Toggle tasks as completed with a checkbox.

Delete Tasks: Remove tasks individually.

Clear Completed: Remove all completed tasks in one click.

Filter Tasks: View All, Active, or Completed tasks.

Priority Highlighting: Tasks are visually highlighted based on priority.

Dark/Light Mode: Switch between themes with a single click.

Items Counter: Shows the number of remaining tasks.

Date Display: Shows the current date on the interface.

Persistent Storage: Uses localStorage to keep tasks across sessions.

Usage
1. Clone or Download
git clone https://github.com/YomiVeph/My-Todo-app.git


Or download the ZIP and extract it.

2. Open in Browser

Open index.html in your favorite browser. No server is required.

3. Add a Task

Type your task in the input field.

Select a priority from the dropdown (default: Medium).

Click Add Task or press Enter.

4. Manage Tasks

Complete a task: Check the box next to it.

Edit a task: Click on the task text, make changes, then click outside to save.

Delete a task: Click the ❌ button.

Clear completed: Click the Clear Completed button to remove all done tasks.

Filter tasks: Use the All / Active / Completed buttons.

5. Theme Toggle

Click the theme button to switch between Dark Mode and Light Mode. The selected theme is saved in localStorage.

6. Priority Colors

Low: Green

Medium: Yellow

High: Red

Tasks are styled differently based on priority for better visibility.

Code Overview

todos Array: Holds all tasks with { id, text, completed, priority }.

localStorage Integration: Saves and retrieves tasks automatically.

Event Listeners: Handles adding, editing, deleting, toggling, filtering, and theme changes.

Dynamic Rendering: renderTodos() updates the DOM based on current tasks and filter.

Date Display: Shows current date using toLocaleDateString.

Future Improvements

Drag-and-drop task ordering.

Task due dates and reminders.

Subtasks or nested tasks.

Sync across devices using backend or cloud storage.

Author

Abayomi Odusanya – GitHub
