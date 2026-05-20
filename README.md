# Todo List

A clean, lightweight Todo List app built with vanilla HTML, CSS, and JavaScript. It lets users add tasks with due dates, view them in a simple grid layout, and remove completed or unwanted tasks instantly.

## Preview

This project is a browser-based task manager with no frameworks, build tools, or external dependencies. Open the HTML file and start organizing tasks immediately.

## Features

- Add todo items with a task name and due date
- Delete tasks with a single click
- Dynamic rendering with JavaScript
- Simple grid-based layout for easy scanning
- Fully client-side implementation
- No installation or setup required

## Tech Stack

- HTML5
- CSS3
- JavaScript

## Project Structure

```text
todo-list Project/
|-- README.md
|-- todo-list.html
|-- todo-list.css
`-- todo-list.js
```

## Getting Started

1. Clone or download this repository.
2. Open `todo-list.html` in your browser.
3. Add a task name, choose a due date, and click **Add**.

No package manager, server, or build step is required.

## How It Works

The app stores todos in an in-memory JavaScript array. When a task is added or deleted, the list is re-rendered into the page using DOM updates.

Core flow:

1. User enters a task and due date.
2. JavaScript pushes the todo object into `todoList`.
3. `renderTodoList()` rebuilds the visible list.
4. Delete buttons remove items by index and refresh the UI.

## Possible Improvements

- Persist todos with `localStorage`
- Add input validation for empty tasks
- Support editing existing tasks
- Add completed task status
- Improve responsive styling for mobile screens
- Add filtering by upcoming, completed, or overdue tasks

## Screenshots

Add a screenshot here after opening the app in your browser:

```text
assets/screenshot.png
```

## Author

Created as a simple, practical JavaScript project for learning DOM manipulation, event handling, and dynamic UI rendering.

## License

This project is open for learning, modification, and personal use.
