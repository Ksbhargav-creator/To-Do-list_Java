# To-Do-list_Java
This project is a desktop-based To-Do list application built using Swing that allows users to manage daily tasks through an interactive GUI.

---

## Features

- User can add new tasks  
- User can see the current list of tasks  
- User can modify or delete existing tasks  
- User can mark tasks as completed  
- If a database (like MySQL) is included, the user can view tasks sorted by date  

---

## Tech Stack

- Java – For Object-Oriented Design  
- Java Swing – For building the graphical user interface  
- MySQL – Can be integrated for long-term task storage and date-based filtering  

---

## Project Structure (Tentative)

```text
TodoGUI/
│
├── Main.java          # Application entry point
├── TodoGUI.java       # GUI components and event handling
├── Task.java          # Task model class
├── TaskManager.java   # Task management logic
└── README.md
```

---

## GUI Components

We are using Swing components to build the interface:

- **JFrame** – Serves as the main application window  
- **JPanel** – Organizes and groups related UI components  
- **JTextField / JTextArea** – Allows users to enter or edit task descriptions  
- **JButton** – Triggers actions such as adding, deleting, or updating tasks  
- **JList (or JTable)** – Displays the list of tasks  
- **JCheckBox** – Allows users to mark tasks as completed  
- **JLabel** – Displays text labels and instructions within the interface  

---

## Layout Management

Layout managers are used to control how components are arranged within the GUI.  
In this project, layout managers ensure that the interface remains structured and organized.

Common layout managers that can be used in this application include:

- **BorderLayout** – Divides the window into regions (North, South, East, West, Center)  
- **FlowLayout** – Arranges components in a left-to-right flow  
- **GridLayout** – Organizes components in a grid of rows and columns  
- **GridBagLayout** – Provides flexible and advanced grid-based positioning  

These layout managers help maintain a clean, responsive interface while keeping the code modular and readable.

---

## Data Handling

- Tasks are stored in memory using an ArrayList or similar collection  
- Each task is represented as a Task object  
- TaskManager manages operations such as adding, updating, deleting, and retrieving tasks  

---

## Future Enhancements

- Integrate MySQL for long-term task storage  
- Enable filtering tasks by creation date or due date  
- Add task prioritization  
- Implement search functionality  

---

## Basic Architecture
The basic console to-do needs a menu system and an array.
The array will be used to store the user input and we can also remove some of the tasks. As this is currently a console based application, we can add in that as a menu system option.
The menu system will look like this:
1. Add Tasks
2. View Tasks
3. Remove Tasks
4. Exit

The menu system class will be run on loop and switch-case statement for now. The tasks will be added and removed using dynamic arrays. For user input we'll use Scanner input.
The above architecture is only for a console based application.
