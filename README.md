# COMP201 - Lab 01 

In order to gain more hands-on experience with the linux shell, following exercise is designed. It is required to perform this exercise and push your resulted file structures to the GitHub classroom by end of the lab session. You are required to perform all operations using the linux shell.

1. Clone the exercise repository by executing the following command:
	```
	$ git clone git@github.com:Farzin-Negahbani/COMP201-F20-Lab01.git
	```
2. Open hello.c file in your terminal and change the "printf" function to print "Welcome to the COMP201 Lab01". Then compile the hello.c code with `$make` command and run the code.
    
3. Make a new directory under doc folder named "info".

4. Use terminal commands to get a list of folders inside "resources" folder and further use piping and connect output list to another program that searches for directories that has string "add" inside and redirects the results to the file named "info.txt" under info folder.

5. Like the previous step, extract the list of folder names but this time look for folders with string "opencv" in their names but in a case-insensitive manner and append the results to the "info.txt" under info folder. Hint: use "--help" option and look for any useful information.

6. Append current date and time and your name to the end of "info.txt".

7. Use "--help" or `$man touch` command and check the use case of `$touch` command. Then, under the "scripts" folder, make a file named "script.sh" and write the following lines one by one to the file (Optional: you can also check the documentation of `$echo` there is an option that you can enable for interpreting "\\n". Then you can add all lines in one command).

```
#!/bin/bash
echo -e "Hello there! How do you feel about bash scripting?"
read
echo "You said $REPLY. Lab exercise 1 is done! Thank you!"
echo $(uname -a) >> ../doc/info/info.txt
```
You can run a bash script using `$bash` command so run the script and answer a simple question and you are done with the first exercise.

[![Run on Repl.it](https://repl.it/badge/github/Farzin-Negahbani/COMP201-F20-Lab01)](https://repl.it/github/Farzin-Negahbani/COMP201-F20-Lab01)
