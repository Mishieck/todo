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

### Bigginer

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
  instructions. For a CLI program, the information must contain the program
  name and instructions for displaying help information as described below.
  For a GUI program. The app name is enough. You can also include a tag-line
  and a logo if you want.
- Display input field: The program must show an input field. For a CLI program,
  the input can be just a caret. You can also prefix the caret with a symbol or
  text indicating that it is an input caret. For a GUI program, display a text
  input and a button. The text input is for entering the todo, and the button
  is for submitting the todo.
- Display help information: The program must display help information when the
  user asks for it. The information must contain instructions on how to use the
  program. All important actions that the user can take must be included. For a
  CLI program, the help information should include all the commands that the
  user can type into the command line to do what they want. The user must
  request this information by typing a command in the input field. For a GUI
  program, the instructions must include descriptions of the features of the
  app. As for the actions, you should count on the GUI being intuitive enough
  for the user to know what to do. The GUI must contain a button that when
  clicked shows the information. This information should be shown on the home
  page of the app (for simplicity). The user must be able to hide the
  information when shown.
- Create a todo: The user must be able to create a todo. The user must be
  able to enter the todo in the input field and submit it. For a CLI program,
  the todo can be submitted by pressing enter (or a similar command). The user
  should be informed that the todo was created by displaying a message.
  For a GUI program, the todo can be submitted by pressing the submit button
  (or by pressing `enter`).
- Display todos: The program must display the todos that the user has created.
  for a CLI program, the user must enter a command that displays the todos. The
  todos must be displayed as a numbered list with the first item being number
  `1`. For a GUI program, the list must be displayed on the home page (for
  simplicity) below the input field. This must be accomplished by clicking a
  button.
- Update a todo: The program must allow the user to update a todo status. The
  status indicates whether or not the todo was done. For a CLI program, you can
  append a star at the end of the todo, or show a pair of square brackets after
  the numbering, where the todos that have been done have an x between the
  brackets and those that haven't have a space. the user must enter a command
  to update a todo. The program must then show a list of the todos. The user
  should then select the todo they want to edit (by entering its position). The
  program must then provide an input field to the user. When the user submits
  the position, the program must toggle the status of the todo, that is to say,
  change it to true if it was false, and vice versa. For a GUI program, each
  todo must have a checkbox that can be used to change the status of the todo.
- Delete a todo: The program must be able to delete a todo. For a CLI program,
  the user must enter a command for deleting a todo. The program must then
  display all todos. The user must then enter the position of the todo they'd
  like to delete. The program must then delete the todo. For a GUI program, each
  displayed todo must must have a delete button.
- Clear todos: The program must allow the user to delete all todos. For a
  CLI program, the user must enter the command for clearing todos. The
  program must then ask the user for confirmation. After confirming, all todos
  should be deleted. For a GUI program, there can be a clear button for this
  purpose. When the user clicks the button, there should be a dialog asking the
  user for confirmation. After confirmation, the todos must be cleared.
- List update: For a GUI program, update the list every time the user adds,
  updates, or deletes a todo.

##### Optional

The program may have the following features:

- Number of todos: The program displays the number of todos when displaying them.
  It also displays the number of todos that have been done.

### Intermediate

### Advanced
