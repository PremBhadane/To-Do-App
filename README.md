# 📅 Tasks App (To-Do List)

A website for a task organizer (to-do list) made with React JS, Tailwind CSS, TypeScript, Redux Toolkit, and more.


## Description

- An application to organize your tasks with the following details: title, description, date, mark as complete, and mark as important. 
- Tasks are organized into routes: today's tasks, important tasks, incomplete tasks, completed tasks, all tasks, and tasks by directory (folder). Both directories and tasks can be edited or deleted. In addition, there is a main directory called "Main" that cannot be edited or deleted.
- The task list can be displayed sorted by: closest dates, furthest dates, completed, or incomplete.
- You can search for tasks using the search field.
- Today's tasks are shown in the user section and in notifications.
- The task data, directories, and dark mode setting are saved in localStorage.

## Objective
The main objective of this project was to put into practice knowledge of TypeScript, Tailwind, Redux Toolkit, and React JS.

- Tools Used
- React JS
- TypeScript
- Tailwind CSS
- Redux Toolkit
- React Router DOM
- HTML
- Figma (prototyping)

## How to Test
You can access the project here: https://to-do-app-premb.netlify.app/

Or run it on your machine: 

``` 
git clone https://github.com/PremBhadane/To-Do-App.git
cd tasks-app
npm install
npm start
```

## Notes
- The data for tasks, directories, and dark mode are stored in your browser's localStorage. You can click the "delete all data" button to remove them.
- For demonstration purposes, the application includes a default list of 3 tasks and 1 directory called "Main".