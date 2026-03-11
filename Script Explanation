# To-Do List Web App (DOM Project)

## Project Overview

This is a simple **To-Do List web application** built using **HTML, CSS, and JavaScript**.
The main goal of this project is to understand how **JavaScript interacts with the DOM (Document Object Model)** to dynamically create, modify, and delete elements on a web page.

Users can add tasks, mark them as completed, delete them, and the tasks are stored using **localStorage**, so they remain even after refreshing the page.
-------------------------------------------------------------------------------------------------------------------
## Features
✔ Add new tasks
✔ Delete tasks
✔ Mark tasks as completed using a checkbox
✔ Press **Enter key** to add a task
✔ Store tasks using **localStorage** so they persist after refresh

---

## Introduction to DOM
 Dom contains various methods and properties that allow us to manipulate the structure, style, and content of a web page.
It provides a way to interact with HTML elements, modify their attributes, and respond to user interactions.

JavaScript can use the DOM to:

* Access HTML elements
* Modify content
* Change styles
* Add or remove elements dynamically
* Respond to user actions like clicks or key presses

In this project, JavaScript uses DOM methods such as:

* getElementById() → to access HTML elements
* createElement() → to create new elements dynamically
* appendChild() → to add elements to the page
* addEventListener() → to handle user interactions
---------------------------------------------------------------------------------------------------------------
## Script Explanation
### 1. Selecting DOM Elements
JavaScript first selects the required HTML elements using their IDs.
* Task input field
* Add Task button
* Task list container

This allows JavaScript to control these elements.
-------------------------------------------------------------------------------------------------------------------------
### 2. Adding Tasks
When the user clicks the **Add Task** button or presses **Enter**, a new task is created.
The script dynamically creates:

* A list item (`li`)
* A checkbox
* A text element (`span`)
* A delete button

These elements are added to the task list using DOM manipulation.
-----------------------------------------------------------------------------------------------------------------------------------
### 3. Marking Tasks as Completed
Each task has a **checkbox**.
When the checkbox is selected:

* The task text gets a **line-through**
* The text color becomes **gray**

This visually shows that the task is completed.
-------------------------------------------------------------------------------------------------------------------
### 4. Deleting Tasks
Each task has a **Delete button**.
When the button is clicked:

* The task is removed from the list
* The updated task list is saved again to localStorage.
---------------------------------------------------------------------------------------------------------------
### 5. Saving Tasks (localStorage)
//local storage: Local storage is a web storage mechanism that allows you to store data in the browser.
It provides a way to save key-value pairs, and the data persists even after the browser is closed.
In this code, we use local storage to save the list of tasks so that they can be retrieved when the page is reloaded.
The application stores tasks in the browser using **localStorage**.

Steps:
1. All task texts are collected from the list.
2. They are stored in an array.
3. The array is converted into a JSON string.
4. The string is saved in localStorage.
------------------------------------------------------------------------------------------------------------------------
### 6. Loading Tasks After Refresh
When the page loads:
* The script retrieves tasks from localStorage.
* Each task is recreated dynamically using DOM elements.
* The tasks appear again on the screen.
-----------------------------------------------------------------------------------------------------------------------
## Technologies Used
* HTML
* CSS
* JavaScript
* DOM Manipulation
* Browser LocalStorage
