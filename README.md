# Python Task Tracker App

# The Python Task Tracker App is a simple command-line application built to help you manage your tasks efficiently.

# Features
Add Tasks: Easily add tasks with a title and description.
List Tasks: View all your tasks along with their details.
Mark Tasks as Complete: Keep track of completed tasks.
Delete Tasks: Remove tasks you no longer need.
Search Tasks: Find specific tasks using keywords.
Installation
Make sure you have Python 3 installed on your system.

# Clone this repository to your local machine:

bash
Copy code
git clone https://github.com/your-username/task-tracker.git
Navigate to the project directory:

bash
Copy code
cd task-tracker
Install dependencies using pipenv:

bash
Copy code
pipenv install
Usage
Adding a Task
To add a task, run:

bash
Copy code
pipenv run python task_tracker.py add "Task Title" "Task Description"
Replace "Task Title" and "Task Description" with your task's actual title and description.

Listing Tasks
To list all tasks, run:

bash
Copy code
pipenv run python task_tracker.py list
This will display all your tasks along with their details.

# Marking a Task as Complete
To mark a task as complete, run:

bash
Copy code
pipenv run python task_tracker.py complete <task_id>
Replace <task_id> with the ID of the task you want to mark as complete. You can find the task ID from the task list.

Deleting a Task
To delete a task, run:

bash
Copy code
pipenv run python task_tracker.py delete <task_id>
Replace <task_id> with the ID of the task you want to delete. You can find the task ID from the task list.

Searching for Tasks
To search for tasks containing specific keywords, run:

bash
Copy code
pipenv run python task_tracker.py search "keyword"
Replace "keyword" with the word you want to search for.

Contributing
Contributions are welcome! If you have any suggestions or find any issues, please feel free to open an issue or submit a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.

This README provides an overview of the task tracker app, installation instructions, usage guide, information on contributing, and licensing details. Users can easily follow 