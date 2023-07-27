FUNCTIONS OF EACH SCRIPT

echo ""(Ôo)'" == displays a confused smiley "(Ôo)'.

cat /etc/passwd == display the content of the /etc/passwd file.

cat /etc/passwd /etc/hosts == display the content of /etc/passwd and /etc/hosts.

tail /etc/passwd == Display the last 10 lines of /etc/passwd.

head /etc/passwd == Display the first 10 lines of /etc/passwd.

head -n 3 iacta | tail -n 1 == displays the third line of the file iacta .

echo "Best School" > \*\\"'"Best School"\'"\\*$\?\*\*\*\*\*:) == creates a file named exactly *\'"Best School"'\*$?*****:) containing the text Best School ending by a new line.

ls -la > ls_cwd_content == writes into the file ls_cwd_content the result of the command ls -la.

tail -n 1 iacta >> iacta == Writes a script that duplicates the last line of the file iacta.

find . -type f -name "*.js" -delete == deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.

find . -type d -not -name '.' | wc -l == counts the number of directories and sub-directories in the current directory.

ls -t1 | head -n 10 == displays the 10 newest files in the current directory.

sort | uniq -u == takes a list of words as input and prints only words that appear exactly once.

grep -i "root" /etc/passwd == Display lines containing the pattern “root” from the file /etc/passwd .

grep -c -i "bin" /etc/passwd == Display the number of lines that contain the pattern “bin” in the file /etc/passw.

grep -i "root" -A 3 /etc/passwd == Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.

grep -i -v "bin" /etc/passwd == Display all the lines in the file /etc/passwd that do not contain the pattern “bin”.

grep -i "^[a-z]" /etc/ssh/sshd_config == Display all lines of the file /etc/ssh/sshd_config starting with a letter.

tr "A" "Z" | tr "c" "e" == Replace all characters A and c from input to Z and e respectively.

tr -d "cC" == removes all letters c and C from input.

rev == reverse its input.

cut -d ':' -f 1,6 /etc/passwd | sort == displays all users and their home directories, sorted by users.
