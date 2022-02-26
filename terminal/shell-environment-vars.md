# Shell environment variables

1. What is a shell environment variable?

- Environment variables are variables that are defined by the current shell and they are inherited by any child shells or processes.
- `printenv`
- A term variable

2. What character is always in front of an bash environment variable name?

- `$`

3. Are shell variable names case-sensitive?

yes, must always be capitalized

## Common cross-platform variables

### `$PATH`

1. What does the `$PATH` variable contain? executable files that reside on your system
2. How does your system use the `$PATH` variable? `echo $PATH`

### `$HOME`

1. What does the `$HOME` variable contain? the location of the home directory
2. Give an example of its usage in a command. Detail what the command would do.
   `cd $HOME`: Change to home directory (from anywhere)

### `$SHELL`

1. What does the `$SHELL` variable contain? the location of where the files that run the current shell are

### `$USER`; Windows: `$USERNAME`

1. What does the `$USER/$USERNAME` variable contain? The account name of the user
