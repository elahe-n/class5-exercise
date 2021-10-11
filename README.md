# Part 1

## Instructions
- Start by creating a new folder and initializing it as a Git repository.
- Copy this file and its contents into your new repository and commit. The copied file should also be named `README.md`.
- Answer the questions below. Introduce each answer as a separate commit.
- Push the resulting repository to your personal GitHub account.
- See the class page for additional submission instructions.

## Questions
1. Write the command (or commands) that will display the following message 'Hello from the command line.'
echo "Hello from the command line."

2. Write the command (or commands) that will create a file named 'hello-world.txt'.
touch hello-world.txt

3. Write the command (or commands) that will create a folder named 'my-new-folder' in _current_ directory.
mkdir my-new-folder
(by cd . command we can navigate to the current folder and then make a new folder, but because we are in the current folder, this command does not make any differences and we can ignore it and make a new folder)

4. Write the command (or commands) that will attempt to delete a folder named 'my-nonexistent-folder' and display the following message when the commands _fails_: 'Whoops, cannot delete a folder that does not exist'.
rmdir my-nonexistent-folder || echo "Whoops, cannot delete a folder that does not exist"

5. Write the command (or commands) that will navigate to your desktop, and then to the parent folder of the desktop.
1: By running 2 commands after each other:  
first run this command: cd ~/Desktop 
second run this command: cd ..
2: Or by running one command. if first part executed successfully, second part will be executed.
cd ~/Desktop && cd ..
