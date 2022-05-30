# bash_scripts_tasks
##Task Day1:

##Activity 1:
1. Create a script that asks for user name then send a greeting to him.
2. Create a script called s1 that calls another script s2 where:
a. In s1 there is a variable called x, it's value 5
b. Try to print the value of x in s2 .
3. Create a script called mycp where:
a. It copies a file from directory to another
b. It copies multiple files from directory to another.
4. Create a script called mycd where it change directory to the given argument directory.
5. Create a script called myls where it lists the given argument directory.
6. Create a script to get number from user and add 1 to it and print it.
7.  Design script to print the current logged in user
8.  Design script to print content of file /etc/password
9.  Script to sort content of file /etc/passwd based on the user id

10. Script to sort content of file /etc/passwd based on user name alphabet
11. Script to sort all integer input argument from high to low



##Activity 2:
Using sed utility
1-  	Display the lines that contain the word “lp” in /etc/passwd file. 
2-  	Display /etc/passwd file except the third line.
3-	Display /etc/passwd file except the last line.
4-	Display /etc/passwd file except the lines that contain the word “lp”.
5-	Substitute all the words that contain “lp” with “mylp” in /etc/passwd file

Using awk utility
1-	Print full name (comment) of all users in the system.
2-	Print login, full name (comment) and home directory of all users.( Print each line preceded by a line number)
3-	Print login, uid and full name (comment) of those uid is greater than 500 
4-  	Print login, uid and full name (comment) of those uid is exactly 500
5-  	Print line from 5 to 15 from /etc/passwd 
6-        Change lp to mylp
7-  	Print all information about greatest uid. 
8-  	Get the sum of all accounts id’s.





##Task Day 2:

##Activity 3:
1. Write a script called mycase, using the case utility to checks the type of character entered by a user: 
a. Upper Case. 
b. Lower Case. 
c. Number. 
d. Nothing. 

2. Enhanced the previous script, by checking the type of string entered by a user: 
a. Upper Cases. 
b. Lower Cases. 
c. Numbers. 
d. Mix. (Upper and lower cases)
e. Nothing. 

3. Enhanced the previous script, by checking the type of string entered by a user: 
a. Upper Cases. 
b. Lower Cases. 
c. Numbers. 
d. Mix. (Upper and lower cases, numbers)
e. Nothing. 

4. Design a script that accept 3 arguments (option [-i, -c, -d], word, file) based on the option if it:
-i: print the lines that contain the given word.
-c: print the number of matched given word.
-d: print the file after deleting the lines that contain the given word.

5. Write a script called myfruit, using the case and select utility to list fruit option (apple, banana and kiwi):
if select apple option, list another three options for me (red, yellow, green) and after selection return to first list.
if select banana option, list another two options for me (yellow, green) and after selection return to first list.
Break the script when select quit option
6. Design a script using the case and select utility to list some countries and when we select a country it print the language of that country.
7. Create a Bash script which will take 2 numbers as command line arguments. It will print to the screen the larger of the two numbers.
8. Create a Bash script which will accept a file as a command line argument and analysis it in certain ways. e.g. you could check if the file is executable or writable. You should print a certain message if true and another if false.
9. Create a Bash script which will print a message based upon which day of the week it is (e.g. 'Happy weekend day' for Friday and Saturday).



















##Task Day 3:

##Activity 4:
1. Write a script called mychmod using for utility to give execute permission to all files in your home directory. 
2. Write a script called mybackup using for utility to create a backup of only files in your home directory. 
3. Design script that used to reset user password
	- You will get the user id
	- If user id no exist ask him to re-enter valid id, if exist
	- Ask user to enter old password if right ask him for new password and then update it to the DB, if not ask him to re-enter the right old password.
  
 
##Challenge 1:
Create a directory with a name of <yourName>-<currentDate>.
Write a bash script to:
Create twenty-five empty (0 KB) files (Hint: Use the touch command).
The file names should be <yourName><number>, <yourName><number+1>, <yourName><number+2> and so on.
Design the script so that each time you execute it, it creates the next batch of 25 files with increasing numbers starting with the last or max number that already exists.
Do not hard code these numbers. You need to generate them using automation.
Test the script. Display a long list of the directory and its contents to validate that the script created the expected files.




##Challenge 2:
Design script that:
Get first name (str) , second name (str), phone number (int), Department (str), Salary (int)
Validate for input type, reject what’s not matched the input type
Don’t accept duplicated phone number
Save new employee record in your database file
Print the insertion done successfully



