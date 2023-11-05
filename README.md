# To-do List App

This is a simple to-do list application built with HTML and CSS. It allows you to add, mark as completed, and delete tasks.

## Usage

1. Open the `index.html` file in your web browser.

2. Type your task in the input box and click "Add" to add it to the list.

3. Click on a task to mark it as completed (or uncompleted).

4. Click on the "X" symbol to remove a task from the list.

## Code

Here's the code for the application:

### HTML (index.html)

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>To-do List App - Easy Tutorials</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Edu+TAS+Beginner&family=Righteous&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
</head>
<body>
<div class="container">
    <div class="todo-app">
        <h2>To-do List
            <img src="images/to-do-list.png" alt="This is an icon" >
        </h2>
        <div class="row">
            <input type="text" id="input-box" placeholder="Add your text">
            <button onclick="addTask()">Add</button>
        </div>
        <ul id="list-container">
            <!-- Task items will be added here -->
        </ul>
    </div>
</div>
<script src="index.js"></script>
</body>
</html>
