#*Description*

A simple UNIX command line interpreter written in C. It allows users to enter commands, which are then executed by the shell. Shell Yeah supports command lines with or without arguments and can handle the PATH. It also includes several built-in commands such as exit and env.

#*Installation*

To install Shell Yeah, follow these steps:

    Clone the repository: git clone https://github.com/Safwat411/Shell_Yeah.git
    Compile the code: gcc -Wall -Werror -Wextra -pedantic *.c -o shell
    Run the shell: ./shell

#*Usage*

Shell Yeah supports several built-in commands, including:

    exit: Exits the shell.
    env: Prints the current environment.
    setenv: Initializes a new environment variable or modifies an existing one.
    unsetenv: Removes an environment variable.
    cd: Changes the current directory of the process.
    alias: Prints a list of all aliases or defines a new alias.

Shell Yeah can also execute external commands by entering their name at the prompt. For example:

shell

$ ls
file1 file2

Shell Yeah supports command lines with or without arguments, and can handle the PATH. For example:

shell

$ /bin/ls
file1 file2
