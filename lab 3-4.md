Experiment 3-4

View the gedit man page. Use the man -k ext4 command to find the command to tune ext4 file-system parameters. Brace expansion is used to generate discretionary strings of characters. Braces contain a comma-separated list of strings,

Approach
To view the gedit manual page, use the man command.
To search for commands related to ext4, use the man -k command.
To use brace expansion, list multiple strings inside {} separated by commas.

Syntax for Commands
View the manual page for gedit:
                      man gedit
Search for commands related to ext4:
                      man -k ext4
Use brace expansion:
                      echo {one,two,three}


Example
Searching for ext4-related commands:
                        man -k ext4
Using brace expansion to generate multiple filenames:
                        touch file{1,2,3}.txt


![image](https://github.com/user-attachments/assets/085549d1-93e1-41c1-94d4-92c019664156)
