This projects contains the following shell scripts for redirecting standard input and output:
	0-hello_world	# prints `Hello World`. followed by a new line to the standard output (remember that each line ends with a newline character)
	1-confused_smiley	# displays a confused smiley "(Ôo)'
	2-hellofile	# displays the content of the `/etc/passwd` file
	3-twofiles	# displays the content of the `/etc/passwd` and `/etc/hosts` files
	4-lastlines	# displays the last 10 lines of `/etc/passwd` file
	5-firstlines	# displays the first 10 lines of `/etc/passwd` file
	6-third_line	# displays the third line of the file `iacta`
	7-file 		# creates a file named exactly `\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)` containing the text `Best School` ending by a new line
	8-cwd_state	# writes into the file `ls_cwd_content` the result of the command `ls -la`
	9-duplicate_last_line	# duplicates the last line of the file `iacta` on the file itself
	10-no_more_js	# deletes all the regular files (NOT directories) with a `.js` extension that are in the current directory and its subfolders
	11-directories	# counts the number of directories and subdirectories in the current directory exclusive of the current and parent directories but inclusive of all hidden directories
	12-newest_files	# displays the 10 newest files in the current directory
	13-unique	# takes a list of words as input and prints only words that appear exactly once. (the output is sorted)
	14-findthatword	# displays lines containing the pattern `root` from the file `/etc/passwd`
	15-countthatword	# Displays the number of lines that contain the pattern `bin` in the file `/etc/passwd`
	16-whatsnext	# displays lines containing the pattern `root` and 3 lines after them in the file `/etc/passwd`.
	17-hidethisword		# displays all the lines in the file `/etc/passwd` that don't contain the pattern `bin`.
	18-letteronly	# displays all the lines of `/etc/ssh/sshd_config starting with a letter (including uppercase letters)
	19-AZ		# replaces all characters `A` and `c` from input to `Z` and `e` respectively. 
	20-hiago 	# removes the letters `c` and `C` from input
	21-reverse	# reverses its input
	22-users_and_homes	# displays all users and their home directories, sorted by users based on the `/etc/passwd` file
