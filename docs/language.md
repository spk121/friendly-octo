For the language to be fun, it has to be able to do the following.

Have a REPL on a UART that can receive functions while the program is running.

For each timed event, each GPIO event, each UART event, there is a hook.
- A function can be attached to a hook.
- Each function attached to a hook is run in order of their priority. For equal priority, oldest first.

