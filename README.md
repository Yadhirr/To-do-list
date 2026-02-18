This is a simple and interactive To-Do List web application built using HTML, CSS, and vanilla JavaScript. The purpose of this project is to demonstrate how to manage tasks dynamically in the browser while using modern JavaScript features like fetch, async/await, DOM manipulation, event handling, filtering, and local storage.

When the application loads, it first checks if there are any saved tasks in the browser’s local storage. If tasks exist, it loads them immediately. If not, it fetches an initial set of example tasks from the public API at JSONPlaceholder (https://jsonplaceholder.typicode.com/todos) and displays them on the screen. This demonstrates how to retrieve data from an external API and render it dynamically in the browser.

Users can add new tasks using the input field at the top of the page. Each task is added instantly to the list without refreshing the page. Tasks can be marked as completed using a checkbox, which visually updates the task with a line-through effect and a different background color. Users can also delete tasks using the trash icon, which includes a confirmation prompt before removal. All changes are automatically saved to local storage so that tasks remain available even after refreshing the page.

The application includes filter buttons in the header that allow users to view:

All tasks

Only active (pending) tasks

Only completed tasks

The interface is clean, minimal, and responsive. It uses simple CSS styling, flexbox layout, subtle shadows, and visual feedback to create a modern user experience. Accessibility is also considered by including proper labels and keyboard support for deleting tasks.

This project demonstrates key front-end development concepts including:

DOM manipulation

Event listeners

Working with APIs

Async/await for asynchronous operations

Local storage for data persistence

Conditional rendering

Basic accessibility practices
