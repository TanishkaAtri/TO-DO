<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>To-Do List</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
        }
        ul {
            list-style-type: none;
            padding: 0;
            text-align: center;
            margin: 10px 0;
        }
        li {
            position: relative;
            cursor: pointer;
            margin: 5px 0;
            padding: 10px 40px 10px 20px; /* Padding inside the box */
            background-color: #f9f9f9;
            border: 1px solid #ddd;
            border-radius: 5px;
            box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.1);
            display: flex;
            justify-content: space-between;
            align-items: center;
            max-width: 400px;
            margin: 10px auto;
        }
        li:hover {
            color: rgb(48, 46, 46);
            background-color: #f1f1f1;
        }
        .header {
            background-image: url('https://i.pinimg.com/736x/4b/7d/0a/4b7d0ad9deeeb8fad8f43b12425f6cb9.jpg');
            background-repeat: no-repeat;
            background-size: cover;
            text-align: center;
        }
        .head {
            padding: 30px;
        }
        .addChecklistBtn {
            border: none;
            width: 150px;
            height: 30px;
            padding: 3px;
            border-radius: 5%;
            box-shadow: 2px 2px 2px black;
            background-color: rgb(126, 61, 61);
            color: white;
            font-weight: bolder;

        }
        #addBtn{
            border: none;
            width: 150px;
            height: 30px;
            padding: 3px;
            border-radius: 5%;
            box-shadow: 2px 2px 2px black;
            background-color: rgb(126, 61, 61);
            color: white;
            font-weight: bolder;
            margin-top: 3%;
        }
        #taskInput {
            height: 20px;
            width: 300px;
            padding: 3px;
            border: none;
            border-radius: 5%;
            box-shadow: 2px 2px 2px black;
        }
        .completed {
            text-decoration: line-through;
            color: gray;
        }
        .close {
            cursor: pointer;
            color: red;
            font-weight: bold;
            padding: 5px;
        }
        .close:hover {
            color: darkred;
        }
        .checklistContainer {
            margin: 20px auto;
            padding: 20px;
            background-color: #f2f2f2;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
            max-width: 450px;
            text-align: center;
        }
        .checklistContainer h2 {
            margin-bottom: 15px;
        }
    </style>
</head>
<body>
    <div class="header">
        <div class="head">
            <h1>My To-Do List</h1> <br>
            <button onclick="addChecklist()" class="addChecklistBtn">Add Checklist</button>
        </div>
    </div>

    <div id="checklistContainerWrapper"></div>

    <script>
        function addChecklist() {
            const checklistContainerWrapper = document.getElementById("checklistContainerWrapper");

            const checklistContainer = document.createElement("div");
            checklistContainer.className = "checklistContainer";

            const checklistTitle = document.createElement("h2");
            checklistTitle.textContent = "New Checklist";
            checklistContainer.appendChild(checklistTitle);

            const taskInput = document.createElement("input");
            taskInput.type = "text";
            taskInput.id = "taskInput";
            taskInput.placeholder = "Enter a new task";

            const addBtn = document.createElement("button");
            addBtn.id = "addBtn";
            addBtn.textContent = "Add Task";
            addBtn.onclick = function() {
                addTask(checklistContainer);
            };

            const taskList = document.createElement("ul");
            taskList.id = "taskList";

            checklistContainer.appendChild(taskInput);
            checklistContainer.appendChild(addBtn);
            checklistContainer.appendChild(taskList);

            checklistContainerWrapper.appendChild(checklistContainer);
        }

        function addTask(checklistContainer) {
            const taskInput = checklistContainer.querySelector("#taskInput");
            const taskText = taskInput.value.trim();

            if (taskText !== "") {
                const listItem = document.createElement("li");

                const taskTextNode = document.createElement("span");
                taskTextNode.appendChild(document.createTextNode(taskText));

                const closeBtn = document.createElement("span");
                closeBtn.className = "close";
                closeBtn.appendChild(document.createTextNode("×"));
                closeBtn.onclick = function() {
                    listItem.remove();
                };

                listItem.appendChild(taskTextNode);
                listItem.appendChild(closeBtn);

                const taskList = checklistContainer.querySelector("#taskList");
                taskList.appendChild(listItem);

                taskInput.value = "";
            }
        }

        document.addEventListener("click", function(event) {
            if (event.target.tagName === 'SPAN' && event.target.className !== 'close') {
                event.target.classList.toggle("completed");
            }
        });
    </script>
</body>
</html>
