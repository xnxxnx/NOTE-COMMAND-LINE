## Some Environment Variable (一些全局变量)


- `~/.bash_profile` : the name of file used to store environment settings
    * `~` represents the user's home directory
    * `.` indicates a hidden file
    * `source ~/.bash_profile` activates the changes in `~/.bash_profile` for the current session
- `alias` : create keyboard shortcuts, or aliases, for commonly used commands
    * `alias hy= "history"`
    * `alias ll = "ls -la"`
- `USER` : usually the user variable is to set the name of computer's owner
- `HOME` : an environment variable that displays the path of the home directory
- `PATH` : an environment variable that stores a list of directories separated by a colon
    * Each directory contains scripts for the command line to execute. The PATH variable simply lists which directories contain scripts
- `env` : environment, returns a list of the environment variables for the cureent user
- `PS1` : a variable that defines the makeup and style of the command prompt

