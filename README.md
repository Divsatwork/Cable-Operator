# Cable-Operator
Tired of using pen and paper to calculate balances, setting datesheet for collection of payments and finding it hard it to maintain the above stuff? You have come to the right place.
Cable Operator Manager eases your work and makes you independent of the standard pen and paper methods used.

Requirements:
1. Java installed (JRE)
2. MySQL installed (You should know root's password so that the program can do the neccessary work)

To Run:
1. Open Command Prompt and then browse to the folder's directory.
2. Then type:
    java -jar <<filename of the application>>
3. If you are running the application for the first time, Click on Menu--> Initialize.
   This will make sure of the backend required for the application to run.
   Note: It'll prompt you to enter the root's password. This is the MySQL's root password. Leave it blank if you think there was no password set to it.

Extra notes:
1. I will include the documentation to import an Excel sheet with records into the database.
2. Please report if any bugs found or if you have any issues in the program.
3. This program considers that every user will have an unique VC Card No. This is basically the primary key according to which the whole software works. Please make sure that your primary attribute(one that can be used to identify anyone) is filled up in this column.
