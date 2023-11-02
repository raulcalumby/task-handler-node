# Task Handler Node

The "Task Handler Node" is a Node.js project that provides an API for managing tasks with CRUD (Create, Read, Update, Delete) operations. This project is useful as an example of implementing RESTful routes in Node.js with the Express framework.

## Features

- Creating new tasks
- Listing tasks
- Updating tasks
- Deleting tasks
- Marking tasks as complete or pending

## Prerequisites

Before you start, make sure you have Node.js installed on your machine.

## Installation

1. Clone the GitHub repository:

git clone https://github.com/your-username/task-handler-node.git


2. Navigate to the project directory:
cd task-handler-node



3. Install the dependencies:
npm install


## Usage

1. Start the server:

npm run dev


2. The server will be running at `http://localhost:3001`.

3. Use an HTTP client such as [Postman](https://www.postman.com/) or [curl](https://curl.se/) to access the available routes.

## Routes

- `POST /tasks`: Create a new task.
- `GET /tasks`: List all tasks.
- `PUT /tasks/:id`: Update an existing task.
- `DELETE /tasks/:id`: Delete a task.
- `PATCH /tasks/:id/complete`: Mark a task as complete or pending.

## Contribution

Feel free to contribute to this project. You can report issues, suggest improvements, or submit pull requests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.


