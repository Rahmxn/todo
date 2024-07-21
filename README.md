## index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>To-Do List</title>
    <link rel="stylesheet" href="style.css">
</head>
<body style="background-image:url(img/240_F_259317013_nJJaBgGGzvXMd6cAyLd6yMJtbdnd61wk\ \(2\).jpg); background-repeat: no-repeat;">
    <div class="container">
        <h1>To-Do List</h1>
        <div class="add-task">
            <input type="text" id="taskInput" placeholder="Add a new task">
            <button onclick="addTask()"><i class="bi bi-plus-circle-fill"></i><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-plus-circle-fill" viewBox="0 0 16 16">
                <path d="M16 8A8 8 0 1 1 0 8a8 8 0 0 1 16 0M8.5 4.5a.5.5 0 0 0-1 0v3h-3a.5.5 0 0 0 0 1h3v3a.5.5 0 0 0 1 0v-3h3a.5.5 0 0 0 0-1h-3z"/>
              </svg> <br>Add</i></button>
        </div>
        
        <ul class="tasks" id="taskList"></ul>
    </div>
    <script src="script.js"></script>
</body>
</html>
```

## OUTPUT

![alt text](<Screenshot 2024-07-07 235055.png>)
![alt text](<Screenshot 2024-07-07 235145.png>)
