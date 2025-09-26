# C Task Manager

A simple **console-based Task Manager** written in **C** that allows you to **add, list, and delete tasks**. Ideal for learning purposes and small task management in a terminal.

---

## Features

- **Add Task** – Add a task with a name (up to 100 characters).  
- **List Tasks** – Display all saved tasks with numbering.  
- **Delete Task** – Remove a task by entering its number.  
- **Exit** – Exit the program gracefully.  

---

## Requirements

- C compiler (e.g., `gcc`)  
- Terminal or console environment  

---

## How to Compile

```
gcc -o task_manager task_manager.c

This will generate an executable called task_manager.
How to Run

./task_manager
```
The program displays a menu:

1. Add Task
2. Delete Task
3. List Tasks
4. Exit
Enter your choice:

    Add Task: Enter the task name when prompted.
   
    Delete Task: Enter the task number from the list of tasks.
   
    List Tasks: Display all current tasks.
   
    Exit: Close the program.

Example Usage
```
Enter your choice: 1
Enter Task Name: Homework
Task added: Homework

Enter your choice: 3
Tasks:
1. Homework

Enter your choice: 2
Enter task number to delete: 1
Deleted task: Homework

```
