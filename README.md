ToDo List in C#
Description
This is a console-based ToDo List application written in C#. It allows the user to create tasks, mark them as completed, edit them, and view a list of all tasks.

Features
Adding new tasks with a description and priority.
Displaying a list of all tasks, sorted by priority.
Marking a task as completed by task number.
Editing a task’s description and priority by task number.
Usage
Upon launching the application, the user is presented with a menu of actions to choose from: add a task, complete a task, display all tasks, edit a task, or exit the application. The user can input their tasks and manage them through the console.


![image](https://github.com/alexeykrymov/ToDo-List-in-C-/assets/55350467/e037d06d-341c-4628-9433-f5436521c0f3)


---------------------------------------------------------------

This code uses the following principles and patterns:

Object-Oriented Programming (OOP) Principles:
Encapsulation: The Task and ToDoList classes encapsulate their data (properties) and methods. For example, the IsComplete property in the Task class is encapsulated using the CompleteTask() method.
Inheritance: Not used in this code.
Polymorphism: Not used in this code.

Properties: In the Task class, the Description, IsComplete, and Priority properties are used to store task information.

Use of switch-case: The Main method in the Program class uses the switch operator to handle user input.

Design Patterns: This code does not use explicit design patterns. However, elements of the “Strategy” pattern can be seen in the AddTask, CompleteTask, RemoveTask, DisplayTasks, and EditTask methods of the ToDoList class, where each method represents a strategy for handling the task list.

Use of Collections: The ToDoList class uses a List<Task> collection to store the task list.

Use of LINQ: The DisplayTasks method in the ToDoList class uses LINQ to sort tasks by priority.

Use of Exceptions: This code does not handle exceptions. For example, when trying to convert user input to a number using int.Parse, an exception may occur if the input cannot be converted to a number. This could be improved by using int.TryParse.

Use of Loops: The DisplayTasks method in the ToDoList class uses a for loop to display all tasks. The Main method in the Program class uses a while loop for an infinite menu cycle until the user chooses to exit.

Use of Conditional Operators: The CompleteTask, RemoveTask, and EditTask methods in the ToDoList class use if conditional operators to check that the task number is within an acceptable range.

Use of Input/Output: This code uses the Console.WriteLine and Console.ReadLine methods for input and output.



Download link for exe:
[https://drive.google.com/file/d/1m7dF5F7cs0lLKhE-7q3pPYB-Z53O5f4o/view?usp=sharing](https://drive.google.com/file/d/1m7dF5F7cs0lLKhE-7q3pPYB-Z53O5f4o/view?usp=sharing)
