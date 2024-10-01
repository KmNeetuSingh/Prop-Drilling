# Todo List Application

📝 A simple Todo List application built with React, demonstrating the use of state management, prop drilling, and component-based architecture.

## Features

- ✅ Add and remove tasks easily.
- 📋 Displays a list of todos with an intuitive UI.
- 💻 Built with React using functional components and hooks.
  
## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/todo-list-app.git
   ```

2. Navigate to the project directory:

   ```bash
   cd todo-list-app
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

## Usage

1. Start the development server:

   ```bash
   npm start
   ```

2. Open your browser and visit `http://localhost:3000` to see the app in action.

## Folder Structure

```plaintext
src/
├── components/
│   ├── TodoForm.js
│   └── TodoList.js
├── App.js
├── App.css
└── index.js
```

## Technologies Used

- ⚛️ **React**: For building the UI and managing the component structure.
- 💅 **CSS**: For styling the components.

## How It Works

- **State Management**: The `App.js` component holds the todo state using `useState`.
- **Prop Drilling**: Todo data is passed from `App.js` to `TodoList` and `TodoForm` via props.
- **Component Breakdown**: `TodoList` displays todos, and `TodoForm` handles adding new todos.

