# website-using-flask
##  The project is a web-based To-Do list application created using the Flask web framework and SQLAlchemy for database management.It allows users to:
### View To-Do List: 
Users can view a list of tasks on the homepage.
### Add New Tasks:
Users can add new tasks to the list by providing a title and description.

### Update Tasks: 
Users can update existing tasks by clicking on an "Update" button associated with each task.

### Delete Tasks: 
Users can delete tasks by clicking on a "Delete" button associated with each task.

The application is structured into four main files:
## app.py: 
This is the main application file, where you have defined your Flask application. The primary functionality includes:

Defining a Flask web application.
Configuring a SQLite database using Flask-SQLAlchemy for storing and managing To-Do items.
Defining a ToDo model to represent To-Do items in the database.

Creating routes for adding, updating, deleting, and displaying To-Do items.
Using templates to render HTML views for adding, updating, and displaying To-Do items.

## index.html: 
This is an HTML template used to display the To-Do list and allow users to add new To-Do items. The template includes a form for adding new tasks and a table for displaying existing tasks.

## base.html:
This is another HTML template that serves as the base template for your web pages. It defines the overall structure of the web pages, including the navigation bar and common elements shared by multiple pages.

## up.html (update.html): 
This is an HTML template used for updating To-Do items. It includes a form with fields for updating the title and description of an existing task.

### The project allows users to perform the following actions:

View a list of existing To-Do items.

Add new To-Do items by providing a title and description.

Update existing To-Do items by modifying the title and description.

Delete To-Do items from the list.

Overall, this project is a simple web-based To-Do list application built with Flask and SQLAlchemy, which allows users to manage their tasks. Users can add, update, and delete tasks through a web interface. This can serve as a foundation for more complex task management applications or as a learning exercise for Flask web development.


