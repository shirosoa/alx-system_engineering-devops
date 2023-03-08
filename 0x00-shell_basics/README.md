/bin/bash: Will tell the terminal to run the script.
pwd: Will print the absolute path of the file we are currently working on.
ls: Will list the contents of your current directory.
cd: Changes directory to user's home directory.
ls -l: Displays current directory content in long format.
ls -a: Displays current directory contents, including hidden files (starting with .). Use the long format.
ls -na: Display current directory contents.
	Long format
	with user and group IDs displayed numerically
	And hidden files (starting with .)
mkdir /tmp/my_first_directory/: Creates a directory named my_first_directory in the /tmp/directory.
mv /tmp/betty /tmp/my_first_directory: Moves the file betty from /tmp/ to /tmp/my_first_directory.
rm /tmp/my_first_directory/betty: Deletes the file betty.
rm -r /tmp/my_first_directory: Deletes the directory my_first_directory that is in the /tmp directory.
cd ..: Changes the working directory to the previous one.
ls -la /root/alx-system_engineering-devops0x00-shell_basics /root/alx-system_engineering-devops /boot: Lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
file /tmp/iamafile/: Prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.
