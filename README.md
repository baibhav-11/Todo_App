# To-Do App using Django

This is a simple To-Do app built using Django, a Python web framework. The app allows users to create, update, and delete tasks on their to-do list.

## Features

- User authentication: Users can sign up, log in, and log out securely.
- Create tasks: Users can add new tasks to their to-do list.
- Update tasks: Users can mark tasks as completed or update task details.
- Delete tasks: Users can remove tasks from their to-do list.
- Task categories: Users can organize tasks by assigning them to categories (e.g., work, personal, groceries).
- Task priorities: Users can set task priorities (e.g., high, medium, low).
- Task due dates: Users can specify due dates for tasks.
- User-friendly interface: The app provides an easy-to-use and responsive interface for managing tasks.

## Getting Started

### Prerequisites

- Python 3.x
- Django 3.x
- pip (Python package manager)

### Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/todo-app.git

2. Navigate to the project directory:
cd todo-app

3. Create a virtual environment (optional but recommended):

python -m venv venv

4. Activate the virtual environment:

On Windows: venv\Scripts\activate
On macOS and Linux: source venv/bin/activate

5. Install project dependencies:

pip install -r requirements.txt

6. Apply database migrations:

python manage.py migrate

7. Create a superuser for administrative access:

python manage.py createsuperuser

8. Start the development server:

python manage.py runserver

Access the app in your web browser at http://localhost:8000/

# Screenshots of App. 

![Django Admin Panel](https://github.com/baibhav-11/Todo_App/assets/114288217/2f22501a-ac7a-4d58-afcb-0fde61e1236b)

First View Of Page.

![Assigning The Task](https://github.com/baibhav-11/Todo_App/assets/114288217/2deaef32-09ca-4c73-9c2f-d72f5ddfbc3c)

Creating a Task Just By Writing Area.

![Creating The Task](https://github.com/baibhav-11/Todo_App/assets/114288217/7100a301-09b5-4030-9889-acc3418b225f)


![Edit The Task](https://github.com/baibhav-11/Todo_App/assets/114288217/389d697a-61de-48cf-94a3-ebad291ea351)

You can also update and rewrite the task by just click on edit button.

![Complete The Assigning Task](https://github.com/baibhav-11/Todo_App/assets/114288217/1b2970c5-1881-4a35-8c46-8b7a59b3ce28)

Complete the Assigning Task and also a icon appearing to show that the task kis completed.

![Deleting The Task](https://github.com/baibhav-11/Todo_App/assets/114288217/91224f71-bcae-4f92-8c5f-595b82792d82)

Click the delete button to delete the task and before deleeting the task a popup is comimg to which it confirms that are you sure want to delete the task.

![After Deleting The Task](https://github.com/baibhav-11/Todo_App/assets/114288217/d0cffd0e-03be-49b2-85a2-e4ae9cf39e7a)

After Deleting The Task


# Usage
- Register a new user account or log in with an existing account.
- Once logged in, you can start adding tasks to your to-do list.
- To create a new task, click the "Add Task" button and fill in the details (title, description, category, priority, due date).
- You can update or delete tasks by clicking on the task and using the provided options.
- Use the navigation menu to filter tasks by category or priority.
- Log out when you are done.

# Contributing
Contributions are welcome! If you would like to contribute to this project, please follow these guidelines:

# Fork the repository.
- Create a new branch for your feature or bug fix: git checkout -b feature-name.
- Commit your changes and push to your fork: git push origin feature-name.
- Submit a pull request to the main repository.

# License
This project is licensed under the MIT License - see the LICENSE file for details.

# Acknowledgments
Django Documentation
Bootstrap
Icons by FontAwesome





