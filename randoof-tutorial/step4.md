# Lets generate the tests using randoop
To make this more structured we are going to create a new directory for this, so we can start of by creating a folder called "Tests" by using the following command in terminal

`mkdir Tests`{{execute}}

Now lets go in the directory by using the command:

`cd Tests`{{execute}}

Now that you are in the right directory we can generate the tests and place them in here.

`java -ea -classpath ../randoop-all-4.3.0.jar:/root randoop.main.Main gentests --testclass=Message`{{execute}}

This should take about a minute to create all the different tests for the Message class.

(You will probobly see many "hi" when executing the given code by us in the terminal. This is the randoop testing the code generating testcases for your program) 
# Clarifications
The structure on how to run the Randoop generation test is by 
`java -ea -classpath <Location of the Randoop jar file>:<Location of the .class file> randoop.main.Main gentests --testclass=<Class file name>`

# Running this on your own computer
To be able to run this on your own computer you need the ranoop jar file which is avalibe here:
https://randoop.github.io/randoop/





