# **To do list**

* ##### **Purpose: This Python script implements a simple command-line to-do list application. It allows users to view, add, remove, and exit tasks in a loop-based menu system.**
* ##### **Language: Python**
* ##### **Execution: The script runs an infinite loop until the user chooses to exit, providing a menu-driven interface for task management.**



* #### **Key Features**



1. ##### **Menu Options:**

* **View Tasks: Displays all current tasks with numbering; shows a message if no tasks exist.**
* **Add Task: Prompts the user to enter a new task, appends it to the list, and confirms addition.**
* **Remove Task: Prompts for a task number, removes it if valid, and confirms removal; handles invalid numbers.**
* **Exit: Prints a goodbye message and breaks the loop.**
* **Data Structure: Uses a Python list (tasks) to store tasks as strings.**
* **Error Handling: Includes checks for invalid menu choices and out-of-range task numbers.**
* **User Interaction: Relies on input() for user choices and task entries, with print() for output.**



##### **2. Code Structure**



**Function: to\_do\_list() – Contains the main logic in a while True loop.**



**Variables:**

* **tasks: An empty list initialized at the start, used to hold task strings.**
* **choice: Stores the user's menu selection.**
* **task: Temporary variable for new tasks.**
* **task\_num: Integer for task removal index.**



##### **3. Control Flow:**

* **Conditional statements (if-elif-else) handle menu options.**
* **Loop continues until exit is chosen.**
* **Output Example:**
* **Menu display: "To-Do List Menu:" followed by numbered options.**
* **Task display: "Your tasks:" with enumerated list (e.g., "1. Buy groceries").**
* **Confirmations: Messages like "Task 'Buy groceries' removed."**
* **Usage Instructions**



* ###### **Run the script in a Python environment (e.g., via command line: python "To do list.py").**
* ###### **Follow on-screen prompts to interact with the menu.**
* ###### **Tasks are stored in memory only; they are lost when the script exits.**
