Welcome to todolist v0.35!
This application allows you to store your tasks in a flexible JSON file so you can access them whenever you need. 
Currently, the app is designed for a single user and requires a Python interpreter to run

The app provides operations to add, delete, mark as done/undone, clear and show all the tasks.

All of the tasks are saved to a local JSON file.

Commands:
/list: displays your complete list of tasks;

/add: create a new task, enter user's task description, then optionally add a due date (in a YYYY-MM-DD format);

/delete [id; integer]: remove a task using its id (one that can be found within the list);

/mark [id; integer]: toggles completion status to done/undone

/clear: permanently delete all tasks from the list;
