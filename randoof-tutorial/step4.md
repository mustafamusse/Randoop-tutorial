# Lets generate the tests using randoop
To make this more structured we are going to create a new directory for this so we can start of by creating a folder called Tests using the following command in terminal

`mkdir Tests`{{execute}}

Now lets go in the directory by using the command:

`cd Tests`{{execute}}

Now that you are in the right directory we can generate the tests in here.

`java -ea -classpath ../randoop-all-4.3.0.jar:/root randoop.main.Main gentests --testclass=Message`{{execute}}

This should take about a minute to create all the different tests for the Message class.
# Clarifications
The structure on how to run the randoop generation test is by 
`java -ea -classpath <Location of the randoop jar file>:<Location of the .class file> randoop.main.Main gentests --testclass=<Class file name>`

The generated tests will be in the folder Tests that can be found by the listed files in visual studio code where we can open and view them.

# Running this on your own computer
To be able to run this on your own computer you need the ranoop jar file which is avalibe here:
https://randoop.github.io/randoop/





