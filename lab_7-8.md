# Experiment :- 7-8.

# Purpose :- 
Create the /home/consultants directory. Add write permission to the consultants group. Use the symbolic method for setting the appropriate permissions. Forbid others from accessing files in the /home/consultants directory. Use the octal method for setting the appropriate permissions. Change the default umask for the operator1 user. The new umask prohibits all access for users that are not in their group. Confirm that the umask is changed.

# Syntax :- 

Create a directory
``mkdir directory_path``

Change permissions using the symbolic method
``chmod g+w directory_path``

Change permissions using the octal method
``chmod 770 directory_path``

Set default umask for a user
``echo "umask value" >> /home/username/.bashrc``

Apply the new umask immediately
``source /home/username/.bashrc``

Check the current umask value
``umask``

# Example :-
```
# Create the /home/consultants directory
mkdir /home/consultants

# Add write permission to the consultants group using symbolic method
chmod g+w /home/consultants

# Forbid others from accessing files in /home/consultants using octal method
chmod 770 /home/consultants

# Set default umask for operator1 user to restrict access for others
echo "umask 007" >> /home/operator1/.bashrc

# Apply the new umask immediately
source /home/operator1/.bashrc

# Verify the current umask setting
umask
```

![image](https://github.com/user-attachments/assets/73aaef10-566c-452f-b450-3203c7124465)
