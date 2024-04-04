# Bigginer

This project focuses on basic language features.

## Skills

This project applies bigginer level skills. The following skills will be applied:

- Syntax
- Data types and structures
- Conditionals
- Repetitions
- Functions
- User interface (CLI or GUI)

## Features

The program will have the following features:

- Let users know how to use the program.
- Enable users to create todos.
- Enable users to view the created todos.
- Enable users to update the statuses of todos.
- Enable users to delete todos.

## Tasks

### Required

The program must have features given in the following sections.

#### Display Welcome Information

When the program starts, it must display some information about the program. 
This can be the program name and instructions.

##### CLI

The information must contain the program name and instructions for displaying 
help information as described below.

##### GUI 

The app name is enough. You can also include a tag-line and a logo if you want.

#### Display Input Field

The program must show an input field. 

##### CLI

The input can be just a caret. You can also prefix the caret with a symbol or 
text indicating that it is an input caret.

##### GUI

Display a text input and a button. The text input is for entering the todo, and 
the button is for submitting the todo.

#### Display Help Information

The program must display help information when the user asks for it. The 
information must contain instructions on how to use the program. All important 
actions that the user can take must be included.

##### CLI

The help information should include all the commands that the user can type 
into the command line to do what they want. The user must request this 
information by typing a command in the input field.

##### GUI

The instructions must include descriptions of the features of the app. As for 
the actions, you should count on the GUI being intuitive enough for the user to 
know what to do. The GUI must contain a button that when clicked shows the 
information. This information should be shown on the home page of the app (for 
simplicity). The user must be able to hide the information when shown.

#### Create a Todo

The user must be able to create a todo. The user must be able to enter the todo 
in the input field and submit it.

##### CLI

The todo can be submitted by pressing enter (or a similar command).

##### GUI

The todo can be submitted by pressing the submit button (or by pressing `enter`).

#### Display Todos

The program must display the todos that the user has created.

##### CLI

The user must enter a command that displays the todos. The todos must be 
displayed as a numbered list with the first item being number `1`.

##### GUI 

The list must be displayed on the home page (for simplicity) below the input 
field. This must be accomplished by clicking a button.

#### Update a Todo

The program must allow the user to update a todo status. The status indicates 
whether or not the todo was done.

##### CLI

You can append a star at the end of the todo, or show a pair of square brackets 
after the numbering, where the todos that have been done have an x between the 
brackets and those that haven't have a space. the user must enter a command to 
update a todo. The program must then show a list of the todos. The user should 
then select the todo they want to edit (by entering its position). The program 
must then provide an input field to the user. When the user submits the position,
the program must toggle the status of the todo, that is to say, change it to 
true if it was false, and vice versa.

##### GUI

Each todo must have a checkbox that can be used to change the status of the todo.

#### Delete a Todo

The program must be able to delete a todo.

##### CLI

The user must enter a command for deleting a todo. The program must then display 
all todos. The user must then enter the position of the todo they'd like to 
delete. The program must then delete the todo.

##### GUI

Each displayed todo must must have a delete button.

#### Clear Todos

The program must allow the user to delete all todos.

##### CLI

The user must enter the command for clearing todos. The program must then ask 
the user for confirmation. After confirming, all todos should be deleted. 

##### GUI

There can be a clear button for this purpose. When the user clicks the button, 
there should be a dialog asking the user for confirmation. After confirmation, 
the todos must be cleared.

#### List Update

For a GUI program, update the list every time the user adds, updates, or deletes 
a todo.

### Optional

The program may have the following features:

#### Number of Todos

The program displays the number of todos when displaying them. It also displays 
the number of todos that have been done.

