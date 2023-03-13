0x02. Shell, I/O Redirections and filters
echo "Hello, World": Prints "Hello, World".
echo "\"(Ôo)'": Prints "(Ôo)'.
cat /etc/passwd: Displays the content of "passwd".
cat /etc/passwd /etc/hosts: Displays the content of "passwd" and "hosts".
tail -n 10 /etc/passwd: Displays the last 10 lines of /etc/passwd.
head -n 10 /etc/passwd: Displays the first 10 lines of /etc/passwd.
head -n 3 iacta | tail -n 1: Displays the third line of the file iacta.
echo "Best School" > \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) : Creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.
ls -la > ls_cwd_content: Writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, creates it.
tail -1 iacta >> iacta: Duplicates the last line of the file iacta.
find . -type f -name "*.js" -delete: Deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
find . -type d ! -path . | wc -l: Counts the number of directories and sub-directories in the current directory.
ls -t . | head: Displays the 10 newest files in the current directory.
sort | uniq -u: Takes a list of words as input and prints only words that appear exactly once.
grep root etc/passwd: Displays lines containing the pattern “root” from the file /etc/passwd.
grep -c root /etc/passwd: Displays the number of lines that contain the pattern “bin” in the file /etc/passwd.
grep -A 3 root /etc/passwd: Displays lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.
grep -i "^[a-z]" /etc/ssh/sshd_config: Displays all lines of the file /etc/ssh/sshd_config starting with a letter.
tr 'Ac' 'Ze': Replaces all characters A and c from input to Z and e respectively.
