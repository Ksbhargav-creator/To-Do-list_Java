# To-Do-list_Java
This project is a desktop-based To-Do list application built using Swing that allows users to manage daily tasks through an interactive GUI.

Features:
1.User can add new tasks.
2.User can modify/delete existing tasks.
3.User can mark completed tasks.

Tech Stack:
1.Java - for Object Oriented Designing
2.Java Swing - for GUI of the app

Project Structure(tentative)
│
├── Main.java # Application entry point
├── TodoGUI.java # GUI components and event handling
├── Task.java # Task model class
├── TaskManager.java # Task management logic
└── README.md

## Basic Architecture
The basic console to-do needs a menu system and an array.
The array will be used to store the user input and we can also remove some of the tasks. As this is currently a console based application, we can add in that as a menu system option.
The menu system will look like this
1.Add Tasks
2.View Tasks
3.Remove Tasks
4.Exit

The menu system class will be run on loop and switch-case statement for now. The tasks will be added and removed using dynamic arrays. For user input we'll use Scanner input.
The above architecture is only for a console based application.
