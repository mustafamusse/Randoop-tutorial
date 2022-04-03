# Lets generate the tests using randoop
To make this more structured we are going to create a new directory for this so we can start of by creating a folder called Tests using the following command in terminal

`mkdir Tests`{{execute}}

Now lets go in the directory by using the command:

`cd Tests`{{execute}}

Now that you are in the right directory we can generate the tests in here.

`java -classpath "../randoop-all-4.3.0.jar" randoop.main.Main gentests --testclass=java.util.TreeSet`{{execute}}

The generated tests will be in the folder Tests that can be found by the listed files in visual studio code where we can open and view them.





