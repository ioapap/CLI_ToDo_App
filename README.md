This is a simple beautiful CLI application, a ToDo App.
The main file to execute is the "main.go" in CMD directory.
To add something to the Todo list use "-add" + whatever task.
To delete something in the Todo list use "-del=1" (whatever task you desire to delete).
To complete a task use "complete=1" (whatever task you desire to complete).
To view the Todo list use "-list".
Of course you can also manually modify/edit the ".todos.json" file and remove/add any task.

![Example](data:image/png;base64,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)
