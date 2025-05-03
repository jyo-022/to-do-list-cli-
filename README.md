📝 To-Do List Application (Command Line)
A simple yet powerful command-line To-Do List application built using Python. This tool helps users manage their tasks by allowing them to add, delete, view, and mark tasks as completed. All data is saved in a tasks.json file for persistence.

📌 Features
     ✅ Add new tasks with descriptions
    🗑️ Delete tasks by their number
    📋 List all tasks with completion status
    ☑️ Mark tasks as completed
    💾 Tasks saved in JSON format
    ⚠️ Basic error handling for invalid commands or inputs

🛠️ Requirements
Python 3.x
No external libraries needed (uses built-in modules)

🚀 How to Run

Clone the repository
git clone https://github.com/your-username/todo-cli-app.git
cd todo-cli-app

Run the script
Use the following commands in your terminal:

Command	Description
python todo.py add "Buy groceries"	Add a new task
python todo.py list	Show all tasks
python todo.py done 1	Mark task 1 as done
python todo.py delete 2	Delete task 2
python todo.py help	Show help instructions

All tasks are stored in tasks.json in the same directory.

📁 File Structure
Copy
Edit
todo-cli-app/
│
├── todo.py         # Main application script
├── tasks.json      # (Generated after you add a task)
└── README.md       # Project documentation


📜 License
This project is open source and available under the MIT License.
