# todo

A guide for using a todo app to learn any programming language from beginner
to advanced.

## Prerequisites

Before starting this project, you must know at least the following
(if supported) about your language:

- Syntax
- Data types
- Conditionals: if statements, switch statements, pattern matching, e.t.c
- Repetitions: loops, recursion, e.t.c
- Functions
- User Interface: communication with the user via a CLI or GUI

## Projects

This project is divided into 3 projects, bigener, intermediate, and advanced.
The projects are prepared in increasing level of complexity. Each subsequent
project builds on the previous project.

All the projects have the following outline:

- Skills: The skills you are required to have before doing the project.
- Features: The features of the projects you be doing.
- Tasks: The tasks you are supposed to do the tasks are of two types:
  - Required: The tasks you have to do.
  - Optional: The tasks you may not do.
- Projects: Examples of projects created.

### Bigginer

This project focuses on basic language features.

#### Skills

This project applies bigginer level skills. The following skills will be applied:

- Syntax
- Data types and structures
- Conditionals
- Repetitions
- Functions
- User interface (CLI or GUI)

#### Features

##### Required

The program must have the following features:

- Display initial information: When the program starts, it must display some
  information about the program. This can be the program name and
  instructions. 
  1. CLI: the information must contain the program name and instructions for 
    displaying help information as described below.
  2. GUI: The app name is enough. You can also include a tag-line and a logo if
    you want.
- Display input field: The program must show an input field. 
  1. CLI: the input can be just a caret. You can also prefix the caret with a 
    symbol or text indicating that it is an input caret.
  2. GUI: display a text input and a button. The text input is for entering the 
    todo, and the button is for submitting the todo.
- Display help information: The program must display help information when the
  user asks for it. The information must contain instructions on how to use the
  program. All important actions that the user can take must be included.
  1. CLI: the help information should include all the commands that the user can
    type into the command line to do what they want. The user must request this 
    information by typing a command in the input field. 
  2. GUI: the instructions must include descriptions of the features of the app. 
    As for the actions, you should count on the GUI being intuitive enough for 
    the user to know what to do. The GUI must contain a button that when clicked 
    shows the information. This information should be shown on the home page of 
    the app (for simplicity). The user must be able to hide the information when 
    shown.
- Create a todo: The user must be able to create a todo. The user must be
  able to enter the todo in the input field and submit it. 
  1. CLI: the todo can be submitted by pressing enter (or a similar command). 
  2. GUI: the todo can be submitted by pressing the submit button (or by pressing 
    `enter`).
- Display todos: The program must display the todos that the user has created.
  1. CLI: the user must enter a command that displays the todos. The todos must 
    be displayed as a numbered list with the first item being number `1`. 
  2. GUI program, the list must be displayed on the home page (for simplicity) 
    below the input field. This must be accomplished by clicking a button.
- Update a todo: The program must allow the user to update a todo status. The
  status indicates whether or not the todo was done. 
  1. CLI: you can append a star at the end of the todo, or show a pair of square 
    brackets after the numbering, where the todos that have been done have an x 
    between the brackets and those that haven't have a space. the user must enter 
    a command to update a todo. The program must then show a list of the todos. 
    The user should then select the todo they want to edit (by entering its 
    position). The program must then provide an input field to the user. When 
    the user submits the position, the program must toggle the status of the 
    todo, that is to say, change it to true if it was false, and vice versa.
  2. GUI: each todo must have a checkbox that can be used to change the status of 
    the todo.
- Delete a todo: The program must be able to delete a todo. 
  1. CLI: the user must enter a command for deleting a todo. The program must 
    then display all todos. The user must then enter the position of the todo 
    they'd like to delete. The program must then delete the todo. 
  2. GUI: each displayed todo must must have a delete button.
- Clear todos: The program must allow the user to delete all todos.
  1. CLI: the user must enter the command for clearing todos. The program must 
    then ask the user for confirmation. After confirming, all todos should be 
    deleted. 
  2. GUI: there can be a clear button for this purpose. When the user clicks the 
    button, there should be a dialog asking the user for confirmation. After 
    confirmation, the todos must be cleared.
- List update: For a GUI program, update the list every time the user adds,
  updates, or deletes a todo.

##### Optional

The program may have the following features:

- Number of todos: The program displays the number of todos when displaying them.
  It also displays the number of todos that have been done.

### Intermediate

You need to create a new project for this. This project builds on top of the
bigginer project. All features from the bigginer project must be included in
this project unless they have been overridden by features in this project. 
This project focuses on developer and user experience.

#### Skills

In this project you will apply the following skills:

- Error and exception handling
- Date and time
- Modules
- File System
- Refactoring

#### Features

##### Required

- Handle errors and exceptions: Inform the user whether or not the action was
  successful. If the action was successful, display as message indicating that.
  If an error or exception occurs, handle it and inform the user of the failure.
  For a CLI program, test the error cases by entering an invalid command or
  enter an invalid position for updating or deleting. For a GUI program, just
  display the success messages. You can use a dialog or alert component.
- Save todos in file: Use a file to store the todos. This will make the todos
  data persist. Update the file as per user actions. On program start, 
  populate the todo data structure with the todos in the file. Use either CSV 
  or JSON format for the files. Do not use a database management system. Use 
  file handling to read and write files. You may use built-in or third party 
  utilites for parsing and serializing the file contents.
- Save time: Save the time at which a todo was created. Display the time to the
  user when displaying todos. Display time in the following format:
  - If the time is within 7 days from the current time, display how long ago
    the time was in seconds, minutes, hours, or days.
  - Otherwise, display the date (without time) in the locale format.
- Use modules: Split your program into two or more files. This makes code
  easier to maintain.
- Select multiple: Enable the user to select more than 1 todo and either mark
  them as done or delete them. For a CLI program, this can be achieved by the
  user submitting more than 1 position. For a GUI app this can be achieved by
  clicking or long-pressing the todos.
- Select all: Let the user select all todos and either mark them as done or
  delete them. For a CLI program, this can be done by entering 0 (as this won't
  be a valid position but a number still). The instructions for doing so must
  be displayed on top of the todo list. For a GUI program, this can be done by
  using a checkbox on top of the todo list. After the user clicks the checkbox,
  the buttons for updating and deleting must appear (or be enabled).
- Refactor your code: make your code more readable and easy to maintain by 
  applying at least the following techniques
  - Variable names: use more descriptive variables. Follow the best practices 
    of your languages in aspects such as cases (camelCase, snake_case, e.t.c.)
  - Single responsibility principle: each function must have one 
    responsibility. If a function has a lot of sub-responsibilites, put each one
    of those responsibilities into separate functions. You can also put 
    functions and data that have related functionality into modules.
  - Syntax: use syntax that is more readable for conditionals, repetitions, and 
    the like.

### Advanced

In this project, you will apply advanced skills. This project builds on top of
the intermediate project. Every features from the intermediate projects will be
included in this project unless it has been overridden by features in this
project. This project focuses on production-ready applications.

#### Skills

The following skills will be applied:

- Dependency management
- Databases
- Testing
- Performance
- Packaging
- Deployment

#### Features

##### Required

- Manage dependencies: Use at least one external dependency. The dependencies
  need to be installed from either the standard library or third-party providers.
  If all utilities in the standard library don't have to be installed, use third-
  party modules. If your language does not have third party dependencies, create 
  modules to simulate this.
- Use a database management system: Create and use a database for the todos. 
  Update the database as per user actions. Use a database management system. If 
  there are neither built-in nor third-party utilities, build your own simple 
  DBM. You can use a remote database if you like.
- Test your code: through out the development process, write tests for your 
  functions, objects, and the like.
- Improve your app's perfomance: rewrite your code to be faster and more memory 
  efficient. You can do this by improving the functions you have written, using 
  different data structrues, or using different build-in utilities. For custom 
  functions and data structures, measure the performance to be sure.
- Package your app: use a package manager and/or compiler to create a package 
  for your app. If your language doesn't support packaging, use NPM or similar 
  tools.
- Deploy your app: publish your app for others to use. If your language does 
  not have the necessary tools for this, use NPM or similar tools.

##### Optional

- Swipe: For a GUI program, add swipe functionality (if possible). Let the user
  swipe right to mark the todo as done. Let the user swipe left to delete a todo.
  The swipe action can take effect immediately or show a button which can be
  clicked to complete the action.

