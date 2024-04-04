# Intermediate

You need to create a new project for this. This project builds on top of the
bigginer project. All features from the bigginer project must be included in
this project unless they have been overridden by features in this project. 
This project focuses on developer and user experience.

## Skills

In this project you will apply the following skills:

- Error and exception handling
- Date and time
- Modules
- File System
- Refactoring

## Features

- Record the time at which a todo was created.
- Handle errors and exceptions.
- Save todos in files for persistent storage.
- Enable users to select multiple todos for manipulation.

## Tasks

### Required

#### Handle Errors and Exceptions

Inform the user whether or not the action was successful. If the action was 
successful, display as message indicating that. If an error or exception occurs, 
handle it and inform the user of the failure.

##### CLI 

Test the error cases by entering an invalid command or enter an invalid position 
for updating or deleting. 

##### GUI 

Just display the success messages. You can use a dialog or alert component.

#### Save Todos in File

Use a file to store the todos. This will make the todos data persist. Update the 
file as per user actions. On program start, populate the todo data structure 
with the todos in the file. Use either CSV or JSON format for the files. Do not 
use a database management system. Use file handling to read and write files. You 
may use built-in or third party utilities for parsing and serializing the file 
contents.

#### Save Time

Save the time at which a todo was created. Display the time to the user when 
displaying todos. Display time in the following format:

- If the time is within 7 days from the current time, display how long ago the 
time was in seconds, minutes, hours, or days.
- Otherwise, display the date (without time) in the locale format.

#### Use Modules

Split your program into two or more files. This makes code easier to maintain.

#### Select Multiple

Enable the user to select more than 1 todo and either mark them as done or 
delete them. For a CLI program, this can be achieved by the user submitting more 
than 1 position. For a GUI app this can be achieved by clicking or long-pressing 
the todos.

#### Select All

Let the user select all todos and either mark them as done or delete them. For a 
CLI program, this can be done by entering 0 (as this won't be a valid position 
but a number still). The instructions for doing so must be displayed on top of 
the todo list. For a GUI program, this can be done by using a checkbox on top of 
the todo list. After the user clicks the checkbox, the buttons for updating and 
deleting must appear (or be enabled).

#### Refactor Your Code

Make your code more readable and easy to maintain by applying at least the 
following techniques

- Variable names: use more descriptive variables. Follow the best practices of 
  your languages in aspects such as cases (camelCase, snake_case, e.t.c.)
- Single responsibility principle: each function must have one responsibility. 
  If a function has a lot of sub-responsibilities, put each one of those 
  responsibilities into separate functions. You can also put functions and data 
  that have related functionality into modules.
- Syntax: use syntax that is more readable for conditionals, repetitions, and 
  the like.

