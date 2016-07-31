# ChatRoom
A very simple chat room application - built upon lessons in book, Head First Java.

### How can I get the code?
Feel free to Fork your own version of this code and play around within the files.

### What are the technical requirements?
Java Standard Edition version 5.0 or higher

### What's Included
Within the download you'll find the following files:
```
SimpleChatClient.java
VerySimpleChatServer.java
```

### How do I run the application?
Download the included .java files into local directory of your choice.  

From the command prompt, compile the java files:  
`javac SimpleChatClient.java`  
`javac VerySimpleChatServer.java`  

In one command prompt, start the chat server:  
`java VerySimpleChatServer`  

In a separate command prompt, Start chat clients, passing in a User Name for each one like so:  
`java SimpleChatClient MisterSchmitz`  

Repeat last step any number of times with different user names.

### Application Features
* Chat client makes use of Threads to simultaneously send outgoing messages while reading incoming messages
