# Bash Practice Challenges

Welcome to the Bash practice challenges! These exercises are designed to help you learn and practice Bash scripting step by step.

## Simple Challenges

1. **Hello World**
   - **Task**: Write a script that prints "Hello, World!" to the terminal.
   - <details><summary>Hint</summary>Look into the `echo` command to print text to the terminal.</details>

2. **Display Current Date and Time**
   - **Task**: Write a script to display the current date and time.
   - <details><summary>Hint</summary>Research the `date` command to find out how to display the current date and time.</details>

3. **Create a Directory**
   - **Task**: Write a script that creates a directory named `my_folder`.
   - <details><summary>Hint</summary>Use the `mkdir` command to create directories.</details>

4. **List Files in a Directory**
   - **Task**: Write a script to list all files in the current directory.
   - <details><summary>Hint</summary>The `ls` command is used to list files in a directory.</details>

5. **Count Files in a Directory**
   - **Task**: Write a script that counts the number of files in the current directory and prints the count.
   - <details><summary>Hint</summary>Combine the `ls` command with `wc` to count lines of output.</details>

## Intermediate Challenges

6. **Rename a File**
   - **Task**: Write a script that renames a file named `old_name.txt` to `new_name.txt`.
   - <details><summary>Hint</summary>Look up the `mv` command for renaming files.</details>

7. **Backup Files**
   - **Task**: Write a script that copies all `.txt` files from the current directory to a directory named `backup`.
   - <details><summary>Hint</summary>Use the `cp` command with a wildcard (`*`) to copy multiple files.</details>

8. **Basic Calculator**
   - **Task**: Write a script that takes two numbers and an operator (`+`, `-`, `*`, `/`) as arguments and prints the result.
   - <details><summary>Hint</summary>Investigate the `expr` command for performing arithmetic operations.</details>

9. **Greet User**
   - **Task**: Write a script that asks for the user's name and then greets the user with their name.
   - <details><summary>Hint</summary>Use the `read` command to get user input and `echo` to print the greeting.</details>

## Moderately Hard Challenges

10. **Word Count**
    - **Task**: Write a script that takes a filename as an argument and prints the number of words in the file.
    - <details><summary>Hint</summary>The `wc -w` command can be used to count words in a file.</details>

11. **Find and Replace in File**
    - **Task**: Write a script that takes three arguments: a filename, a string to find, and a string to replace it with. The script should replace all occurrences of the find string with the replace string in the file.
    - <details><summary>Hint</summary>Look into the `sed` command for search and replace functionality in files.</details>

12. **Check Disk Usage**
    - **Task**: Write a script that checks the disk usage of the current directory and alerts if it is more than a specified limit (e.g., 100MB).
    - <details><summary>Hint</summary>Use the `du` command to check disk usage and an `if` statement to compare values.</details>

13. **Log File Analysis**
    - **Task**: Write a script that extracts and prints the 10 most common IP addresses from a web server log file.
    - <details><summary>Hint</summary>Use `awk` to extract IP addresses, then `sort` and `uniq` to count and list the most common ones.</details>
