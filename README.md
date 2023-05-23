# To-Do Flask App

This is a simple to-do application built with Flask framework. It allows users to create, manage, and track their to-do tasks effectively.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Installation

To install and set up the to-do app, follow these steps:

1. Clone the repository:
git clone https://github.com/marchmello1/to-do-flask-app.git


2. Navigate to the project directory:
cd to-do-flask-app

3. Create a virtual environment:
python -m venv env

4. Activate the virtual environment:
source env/bin/activate # For Linux/Mac
env\Scripts\activate # For Windows

5. Install the dependencies:
pip install -r requirements.txt

6. Set up the database:
flask db init
flask db migrate
flask db upgrade

7. Run the application:
flask run


The app will be accessible at `http://localhost:5000`.

## Usage

Once the application is running, you can access it in your web browser. The main features of the to-do app include:

- Creating a new task
- Viewing the list of tasks
- Updating task status (marking as complete or incomplete)
- Editing task details
- Deleting a task



Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue on the [GitHub repository](https://github.com/marchmello1/to-do-flask-app/issues). If you'd like to contribute code, you can follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/my-feature`.
3. Commit your changes: `git commit -m 'Add my feature'`.
4. Push the branch: `git push origin feature/my-feature`.
5. Submit a pull request.


If you have any questions, feedback, or would like to collaborate, you can reach me at [mohammad.agwan@somaiya.edu].


