# Steven's TODO App

A simple task management application built using **Petite-Vue**, **Tailwind CSS**, **DaisyUI**, and **Material Icons**. It allows users to add, mark as complete, and delete tasks, with a clean and responsive design.

## Features

- **Add tasks**: Users can add new tasks using the input form.
- **Mark tasks as completed**: Click on a task to mark it as complete, which moves the task to the end of the list and visually strikes it through.
- **Delete tasks**: Users can delete completed tasks using the delete button.
- **Dark/Light Mode Toggle**: Toggle between light and dark modes using the theme switcher in the header.

## Technologies Used

- **Petite-Vue**: Lightweight reactivity library used to manage interactivity.
- **Tailwind CSS**: For responsive and utility-first CSS styling.
- **DaisyUI**: A set of UI components built on top of Tailwind CSS.
- **Material Icons**: Icon set used for UI elements such as the theme toggle and delete button.

## Setup

To run this project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/programmerstevie/petite-vue-todo.git
   ```

2. Navigate to the project directory:

   ```bash
   cd petite-vue-todo
   ```

3. Open the `index.html` file in your browser to use the TODO app.

   Alternatively, you can use [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) in VS Code for live reloading.

## How to Use

1. Open the app in your browser.
2. Add a new task by typing into the input box and clicking **Add Task**.
3. Mark a task as completed by clicking on the task. This will move it to the bottom of the list and strike through the text.
4. Delete a task by clicking on the red delete button, but only after it has been marked as completed.
5. Toggle between light and dark mode using the sun/moon button in the header.

## Acknowledgements

- **Petite-Vue**: A lightweight alternative to Vue for handling reactivity.
- **Tailwind CSS** and **DaisyUI**: For providing a flexible and modern CSS framework.
- **Google Material Icons**: For the icons used in the UI.