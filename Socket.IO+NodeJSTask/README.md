# NodeJS Socket.IO Task

Create a notification system using NodeJS and Socket.IO

#### Assignment

  - Create a Socket.IO based application
  - Use mongodb as a persistance layer
  - The application should allow us to view list of all connected users on socket at a time
  - We should be able to create virtual chat rooms for users on backend
  - users can add/remove other users from chat rooms 
  - Users can send message to other users or entire chat rooms he is part of
  - These messages should be persisted in db and when users come back online they should receive the messages intended for them.
  - Chat rooms should be persisted in db layer so when server restarts data is not lost
  - when user connects to socket he should be automatically added to chat rooms he was part of and receive notifications that were shared when he was offline
  - No frontend is necessary
  

##### Directions
-  All functionality is not compulsory. Try to cover as many as possible
-  Use ES6/ES7 for writing code
- Ideal time to finish the project would be 3-5 days
- Email if you have any queries/doubts
- The project is open ended so try to do few Great things then Many Ordinary things
- You should have fun building it. 
- If its not finished submit it anyways. 

##### Before you start
   - Drop an email at kartik@rxlab.solutions with the following details: Name, College, Resume, Proficient Skills, tentative problem statement/features you intend to finish as part of the task and when you will start the project 
    
##### After you finish
- Upload the code on Github/Bitbucket and share the link on email.
- There should be a file detailing how to setup the project, run the tests and any other intructions. 
- A small video of code running successfully would be helpful

##### Bonus

- Authenticate the user who connects to socket and not allow unauthenticated users to join chat rooms
- Users can mark messages as read and only receive unread messages on new connection
