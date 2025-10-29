# To-Do-App-
#  To-Do App with React Hooks

A simple and interactive **To-Do List Application** built using **React** and **React Hooks**.  
This project helps users efficiently manage daily tasks — add, edit, mark as complete, and delete tasks — with a clean and responsive user interface.


##  Features

-  Add new tasks  
-  Edit existing tasks  
-  Delete tasks  
-  Mark tasks as completed or pending  
-  Persistent data using Local Storage  
-  Built entirely with functional components and React Hooks (`useState`, `useEffect`)



##  Technologies Used

- **React JS**
- **React Hooks**
- **JavaScript (ES6+)**
- **HTML5 / CSS3**
- **LocalStorage API**
- **Vite** or **Create React App**


##  Installation & Setup

Follow the steps below to run the project locally:


# 1. Clone the repository
git clone https://github.com/atchayamarimuthu/To-Do-App-.git

# 2. Navigate into the project folder
cd todo-app-react-hooks

# 3. Install dependencies
npm install

# 4. Start the development server
npm start
# or (if using Vite)
npm run dev



# React Hooks Used

| Hook        | Description                                                                  |
| ----------- | ---------------------------------------------------------------------------- |
| `useState`  | Manages state variables such as tasks and form input.                        |
| `useEffect` | Handles side effects such as saving and retrieving tasks from Local Storage. |


# Folder Structure

### Explanation of Key Files and Directories:

* **`src/`**: Contains all the source code for the React application.
    * **`src/components/`**: Houses reusable React components.
        * **`todoform.js`**: Component responsible for adding new todo items.
        * **`todolist.js`**: Component responsible for displaying the list of todo items.
        * **`todoitem.js`**: Component representing an individual todo item.
    * **`app.js`**: The main application component, orchestrating the other components.
    * **`index.js`**: The entry point of the React application, where `App` is rendered.
* **`styles.css`**: Contains global styles for the application.
* **`package.json`**: Defines project metadata and dependencies.
* **`readme.md`**: This file, providing information about the project.
* **`.gitignore`**: Specifies files and directories to be ignored by Git.

## Getting Started

[Provide instructions on how to set up and run the application, e.g., `npm install`, `npm start`.]



#  Future Enhancements

- Task reminders or notifications

- Task filters and categories

- Sync with backend or Firebase

- Dark mode support

