document.getElementById('addTaskButton').addEventListener('click', addTask);

function addTask() {
    const input = document.getElementById('taskInput');
    const taskText = input.value.trim();
    if (taskText === '') return;

    const taskList = document.getElementById('taskList');

    const taskDiv = document.createElement('div');
    taskDiv.className = 'task';

    const span = document.createElement('span');
    span.textContent = taskText;

    const button = document.createElement('button');
    button.textContent = '✓';
    button.onclick = () => {
        taskDiv.classList.toggle('completed');
    };

    taskDiv.appendChild(span);
    taskDiv.appendChild(button);
    taskList.appendChild(taskDiv);

    input.value = ''; // Clear the input field
    document.getElementById('currentYear').textContent = new Date().getFullYear();
}
