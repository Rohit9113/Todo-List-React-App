# TodoList React App

This is a TodoList app built using React. It allows users to fetch, add, update, and delete todo items. The app utilizes the jsonplaceholder API to perform CRUD operations on todo items.

## Host Link
Link :- https://react-todo-list-y9i0.onrender.com/
## Features

The TodoList React app includes the following features:

- Fetch and display todo items from the API.
- Add a new todo item.
- Update an existing todo item.
- Delete a todo item.

## Directory Structure

```

├── node_module/
├── src/
│   ├── api/
│   │   └── index.js
│   ├── components/
│   │   ├── addTask/
│   │   │   ├── AddTask.js
│   │   │   └── AddTask.module.css
│   │   ├── container/
│   │   │   ├── TodoContainer.js
│   │   │   └── TodoContainer.module.css
│   │   ├── showTask/
│   │   │   ├── ShowTask.js
│   │   │   └── ShowTask.module.css
│   │   └── spinner/
│   │       └── spinner.js
│   ├── App.js
│   └── index.css
├── .gitignore
├── package-lock.json
└── package.json

```

The directory structure of the project is as follows:

- `node_module/`: Contains the dependencies and modules installed for the project.
- `src/`: Contains the source code for the React app.
  - `api/`: Contains the file `index.js` which handles API requests and CRUD operations.
  - `components/`: Contains the different components used in the app.
    - `addTask/`: Contains the files `AddTask.js` and `AddTask.module.css` which implement the functionality to add a new todo item.
    - `container/`: Contains the files `TodoContainer.js` and `TodoContainer.module.css` which serve as the main container component for the todo list.
    - `showTask/`: Contains the files `ShowTask.js` and `ShowTask.module.css` which display the list of todo items.
    - `spinner/`: Contains the file `spinner.js` which provides a spinner component for loading states.
  - `App.js`: The main component that renders the app.
  - `index.css`: CSS file for the app.
- `.gitignore`: Specifies which files and directories to ignore in version control.
- `package-lock.json`: Automatically generated file that locks the versions of the installed dependencies.
- `package.json`: Contains the metadata and dependencies of the project.

## Usage

To use the TodoList React app, follow these steps:

1. Clone the repository or download the source code.
2. Open a terminal or command prompt and navigate to the project directory.
3. Run `npm install` to install the necessary dependencies.
4. Run `npm start` to start the development server.
5. Open a web browser and visit `http://localhost:3000` to access the app.

## Credits

The TodoList React app utilizes the jsonplaceholder API for performing CRUD operations on todo items. The API provides a mock RESTful interface for testing and prototyping.

## License

This project is licensed under the [MIT License](LICENSE).
