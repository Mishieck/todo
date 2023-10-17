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

You need to create a new project for this. This project builds on top of the
bigginer project. All features from the bigginer project must be included in
this project unless they have been overridden by features in this project.

#### Skills

In this project you will apply the following skills:

- Handle errors and exceptions: Inform the user whether or not the action was
  successful. If the action was successful, display as message indicating that.
  If an error or exception occurs, handle it and inform the user of the failure.
  For a CLI program, test the error cases by entering an invalid command or
  enter an invalid position for updating or deleting. For a GUI program, just
  display the success messages. You can use a dialog or alert component.
- Save todos in files: Use files to store the todos. This will make the todos
  data persist. Update the files as per user actions. This insures that the user
  can pick up from where they left off. Use either CSV or JSON format for the
  files.
- Save time: Save the time at which a todo was created. Display the time to the
  user when displaying todos. Display time in the following format:
  - If the time is within 7 days from the current time, display how long ago
    the time was in seconds, minutes, hours, or days.
  - Otherwise, display the date (without time) in the locale format.
- Use modules: Split your program into two or more files. This makes code
  easier to maintain.
- Select todo before action: For a CLI program, let the user select a todo from
  the list and then decide what to do with it. This is applicable to updates
  and deletions. This should be the only way a user can update or delete a todo.
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

### Advanced
