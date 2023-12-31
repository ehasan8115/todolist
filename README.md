# Todo List Application

This is a simple web-based Todo List application built with Node.js, Express, and MongoDB.

## Features

- Add and manage tasks in a todo list.
- Create custom lists to organize your tasks.
- Mark tasks as complete or delete them.
- Responsive design for a seamless experience on different devices.

## Installation

1. Clone the repository:

https://github.com/ehasan8115/todolist.git

2. Install the dependencies:

cd todolist
npm install


3. Set up the MongoDB connection:

- Ensure that MongoDB is installed and running on your machine.
- Create a .env file in the root directory and add your MongoDB connection string:

  "mongoose.connect("mongodb://127.0.0.1:27017/todolistDB", { useNewUrlParser: true, useUnifiedTopology: true })"


4. Start the application:

npm start


5. Open your web browser and visit `http://localhost:3000` to access the application.

## Usage

- **Home Page**: Displays the list of tasks in the default "Today" list. You can add new tasks and mark them as complete or delete them.
- **Custom Lists**: You can create custom lists by appending the list name to the URL (e.g., http://localhost:3000/work). Custom lists have the same functionality as the default list.
- **Individual Post Page**: Displays the full content of a blog post.
- **About Page**: Provides information about the todo list application.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.

## Deployment

The project is deployed and accessible at [https://todolist-app-jeh0.onrender.com/]

