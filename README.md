<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple To-Do List</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>To-Do List</h1>
        <div class="input-container">
            <input type="text" id="task-input" placeholder="Enter a new task...">
            <button id="add-task-button">Add Task</button>
        </div>
        <ul id="task-list">
            <!-- Tasks will be added here dynamically -->
        </ul>
    </div>
    <script src="script.js"></script>
</body>
</html>
