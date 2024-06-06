# React To-Do List Application

A simple and intuitive To-Do List application built with React.js. This project demonstrates the basics of React including component creation, state management, and styling.

## Features

- **Add a new task**: Easily add tasks to your to-do list.
- **Mark a task as complete**: Mark tasks as completed or active.
- **Delete a task**: Remove tasks that are no longer needed.
- **Filter tasks by status**: Filter tasks to view all, active, or completed tasks.

## Project Structure

```
todo-app/
├── public/
│   ├── index.html
├── src/
│   ├── components/
│   │   ├── TodoItem.js
│   │   ├── TodoList.js
│   │   ├── AddTodo.js
│   ├── App.js
│   ├── index.js
│   ├── App.css
│   ├── index.css
├── package.json
```

## Installation

Follow these steps to get the project up and running on your local machine:

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) (version 20.14.0 recommended)
- npm (comes with Node.js)

### Steps

1. **Clone the repository:**

    ```bash
    git clone https://github.com/sneakypanda17/to-do-app.git
    cd todo-app
    ```

2. **Install dependencies:**

    ```bash
    npm install
    ```

3. **Start the development server:**

    ```bash
    npm start
    ```

    This will start the React development server and open the application in your default web browser.

## Usage

- **Add Task**: Enter a task in the input field and press `Add` to add the task to the list.
- **Mark Complete**: Click on the task text to toggle between completed and active states.
- **Delete Task**: Press the `Delete` button next to a task to remove it from the list.
- **Filter Tasks**: Use the filter buttons to view all tasks, only active tasks, or only completed tasks.

## Screenshots

![Todo List Screenshot](./screenshots/todo-list.png)

## Contributing

If you would like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the React documentation and the community for their support and resources.
