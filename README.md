# Broadcasting Chat Server
## Objective
This project makes use of Multithreading/Multiprogramming concepts to let the users interact with each other logged in at a given time. The messages shared by the users is broadcasted to all the users logged in. The information regarding new users logging in or users logging out is shared to all other users.
## Implementation
This project makes use of the Java packages like AWT, NET and Swing. The server is created using the ServerSocket class of the java.net package. Event handling classes like ActionListener specifies the functonalities of the components present within the chat window. These are implemented using the the java.awt package. The javax.swing package provides the GUI for the chat window and provides classes like JButton, JFrame, JTextArea, JLabel for the implementation of the different components. Threads are created by implementing the Runnable Interface.
## How to run the Project
Run the server first, write: java MyServer,
now click on the executable jar file MyClient as many as you want. It will open different dialog boxes. Now try to communicate with each other.
Click on the login button and enter your name, now you can share information.
## Welcome Page
![Screenshot (14)](https://user-images.githubusercontent.com/111787164/186024957-72c947c1-dd57-4796-88d2-e74a590438ab.png)
