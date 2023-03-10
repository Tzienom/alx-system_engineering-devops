"echo Hello, World" will print Hello, World to the standard output, with a new line.
"echo "\"(Ôo)'"" displays "(Ôo)'.
"less /etc/passwd" will display the contents of /etc/passwd.

"cat /etc/passwd /etc/hosts | less" will display the contents of specified files.
"tail -10 /etc/passwd" will display the last ten lines.

"head -10 /etc/passwd" will display the first ten lines.
"head -3 iacta | tail -1" will display the third line.

"echo "Best School" > "\*\\\\'\"Best School\"\\'\\\\*$\?\*\*\*\*\*:)"" will create a file named \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) with the "Best School" content in it.

"ls -la > ls_cwd_content" writes the result of ls -la into ls_cwd_content. If the file already exists, it overwrites it, if not, it creates it.

"tail -1 iacta | echo $(tail -1 iacta) >> iacta" duplicates the last line and appends it to the file.
"find . -type f name ".js" -exec rm {} +" searches for all .js files in the current directory, subdirector(y)(ies), and deletes them.

"ls -t | head -10" prints the 10 newest files starting from the newest to oldest.
"sort | uniq -u" sorts the given list and prints non-duplicated lines.

"grep -w "root" /etc/passwd" searches for "root" word occurrence(s) and prints it.
"grep "bin" /etc/passwd | wc -l" prints the number of lines containing "bin".

"grep -A 3 "root" /etc/passwd" prints line(s) with the specified pattern, and also prints the next thre lines after them.
"grep -v "bin" /etc/passwd" prints lines that do not contain the specified pattern.

"grep "^[a-z, A-Z]" /etc/ssh/sshd_config" will display all lines of the file starting with a letter.
"tr "Ac" "Ze"" translates all occurrences of A and c to Z and e respectively.

"tr -d "Cc"" deletes all occurrences of C and c.
"rev" reserves the input it receives.

"cut -d: -f1,6 /etc/passwd" displays the user names' and their home directories.
