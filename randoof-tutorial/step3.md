# Create a simple function
This is a class that takes a message, prints it and returns the message.

`public class Message {
   private String message;
   public Message(String message){
      this.message = message;
   }   
   public String printMessage(){
      System.out.println(message);
      return message;
}}`{{copy}}

These are the functions that we are going to be generating randoop tests for, they can be as simple as these or more complex. You can write your own functions and test if you would like that aswell.   


Now we need to compile the file that we have created, this can be done with the following command.

`javac Message.java`{{execute}}
# What to do
Please copy and paste these functions to add them to the file app.java which was is generated from our previous step.