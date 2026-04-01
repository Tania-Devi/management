<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Student Task Manager</title>

<style>
  body {
    font-family: Arial, sans-serif;
    background: linear-gradient(135deg, #667eea, #764ba2);
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
  }

  .container {
    background: white;
    padding: 20px;
    border-radius: 15px;
    width: 350px;
    box-shadow: 0 10px 25px rgba(0,0,0,0.2);
  }

  h2 {
    text-align: center;
    color: #333;
  }

  input {
    width: 70%;
    padding: 8px;
    border-radius: 8px;
    border: 1px solid #ccc;
  }

  button {
    padding: 8px 12px;
    border: none;
    background: #667eea;
    color: white;
    border-radius: 8px;
    cursor: pointer;
  }

  button:hover {
    background: #5a67d8;
  }

  ul {
    list-style: none;
    padding: 0;
    margin-top: 15px;
  }

  li {
    background: #f4f4f4;
    padding: 10px;
    margin-top: 8px;
    border-radius: 8px;
    display: flex;
    justify-content: space-between;
  }

  .delete {
    background: red;
    padding: 5px 8px;
    border-radius: 5px;
    cursor: pointer;
  }

  .completed {
    text-decoration: line-through;
    color: gray;
  }
</style>
</head>

<body>

<div class="container">
  <h2>📘 Task Manager</h2>

  <input type="text" id="taskInput" placeholder="Enter task">
  <button onclick="addTask()">Add</button>

  <ul id="taskList"></ul>
</div>

<script>
  let tasks = JSON.parse(localStorage.getItem("tasks")) || [];

  function saveTasks() {
    localStorage.setItem("tasks", JSON.stringify(tasks));
  }

  function displayTasks() {
    const list = document.getElementById("taskList");
    list.innerHTML = "";

    tasks.forEach((task, index) => {
      let li = document.createElement("li");

      li.innerHTML = `
        <span onclick="toggleTask(${index})" class="${task.done ? 'completed' : ''}">
          ${task.text}
        </span>
        <span class="delete" onclick="deleteTask(${index})">X</span>
      `;

      list.appendChild(li);
    });
  }

  function addTask() {
    let input = document.getElementById("taskInput");
    if (input.value.trim() === "") return;

    tasks.push({ text: input.value, done: false });
    input.value = "";

    saveTasks();
    displayTasks();
  }

  function deleteTask(index) {
    tasks.splice(index, 1);
    saveTasks();
    displayTasks();
  }

  function toggleTask(index) {
    tasks[index].done = !tasks[index].done;
    saveTasks();
    displayTasks();
  }

  displayTasks();
</script>

</body>
</html>
