# Shortcuts
Shortcuts are an application that allows you to quickly enter a command or a series of commands in a terminal. 
You can save some useful commands like "ls -ASlR | grep -E "^\-rw." | sort -n -t " " -k5 -r | head -n10" and assign it to a shortcut like "biggest_files". Then you can just click on the shortcut and the command will be executed in the terminal.
It is like desktop, but more flexible.


## Features
### Implemented

### Planned
- Variables in application.
For example, you can define a variable `my_dir` and assign it to a path like `/home/user/Downloads`. Then you can use this variable in your shortcuts like `ls /my_dir\` and it will be replaced with `/home/user/Downloads`. This will allow you to easily change the path in all shortcuts where this variable is used.
- Import/export of shortcuts.
- Lazy variable evaluation.
A undefined variable will not cause an error, but will be asked with a dialog to define it. For example, if you have a shortcut `ls $my_dir` and `my_dir` is not defined, the application will ask you to define it.
