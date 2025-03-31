# To-Do-List
A to-do list is generally used list all the task that a person wants or needs to do and then track his progress on it. This is a simple yet effective way to get the work done. In this article, we will learn how to create a console based C++ program to implement to do list. This application will allow you to add, delete, display, edit, and mark tasks as completed.

Features of the To Do List Program
This to do list provides the following features:

Add Tasks: Users can add new tasks to the list, specifying details such as task name, description, and due date.
View Tasks: The program can display all tasks in the list, showing details like task name, description, and status.
Delete Tasks: Users can remove tasks from the list when they are no longer needed or completed.
Mark Tasks as Completed: Tasks can be marked as completed, helping users track their progress and distinguish between pending and finished tasks.
Edit Tasks: Users can modify existing tasks, updating information like the task name, description, or due date
Implementation of the Features
We first created two classes:

Tasks: This represents a single task and all the required methods of it.
ToDoList: This represents the to do list that consists of a tasks list and the methods to provide different features of the project.
Now, we implement the to do list features as shown below:

Add Tasks:
Prompt for task details (name, description, due date).
Create and add a new Task object to the tasks vector.
Confirm task addition.
View Tasks:
Check if tasks vector is empty.
If not, display each task's details using displayTask().
Delete Tasks:
Check if tasks vector is empty.
If not, display task list and prompt for task number to delete.
Validate and delete the selected task.
Mark Tasks as Completed:
Check if tasks vector is empty.
If not, display task list and prompt for task number to mark as completed.
Validate and mark the selected task as completed.
Edit Tasks:
Check if tasks vector is empty.
If not, display task list and prompt for task number to edit.
Validate and prompt for new task details.
Update the task with new details.
