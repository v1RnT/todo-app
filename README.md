# Todo App

This project is a Todo application that allows users to manage their tasks effectively. Including the functionality for adding, editing, filtering, marking as completed your tasks.

You can check out the page by the link: \
[Demo Link](https://v1rnt.github.io/todo-app/)

## Features

**Add Tasks**: Add new tasks to the list. \
**Edit Tasks**: Update task details. \
**Mark as Complete**: Toggle tasks as completed or uncompleted. \
**Filter Tasks**: View tasks based on their status (All, Active, Completed). \
**Delete Tasks**: Remove tasks individually or in bulk. \
**Error Handling**: Displays user-friendly error messages in case of API issues.

## Technologies Used

**React**: Component-based UI library. \
**TypeScript**: Static type checking for JavaScript. \
**CSS/SCSS**: Styling for the application. \
**Fetch API**: For making asynchronous requests to interact with the backend APIs. \
**React Hooks**:

- **useState** for managing state.
- **useEffect** for handling side effects like data fetching.
- **useMemo** and useCallback for performance optimization.

## API Integration

The app uses three API endpoints:

GET /todos - Fetches all todos from the server. \
DELETE /todos/:id - Deletes a specific todo. \
PATCH /todos/:id - Updates a specific todo.

## Installation

Clone the repository:

```bash
git clone https://github.com/v1RnT/todo-app.git
```

Navigate to the directory:

```bash
cd todo-app
```

Before the installation, make sure to set the right version for Node 20:

```bash
node -v
```

After u made sure u have Node 20, feel free to install all dependencies:

```bash
npm i
```

After installation, check the page using:

```bash
npm start
```

## Contacts

Feel free to reach out if you have any questions or feedback:

Telegram: [@v1rnt](https://t.me/v1RnT) \
LinkedIn: [Vitalii Mlynetskyi](https://www.linkedin.com/in/vitalii-mlynetskyi-62823727b/) \
Email: mlynetskyivitalii@gmail.com
