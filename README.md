# WAppBIU Server
Hello!
Welcome to our server!
This server was desgined by Daniel Meir Karl and Dvir Landau

# Turn on the server
To turn on our server, please run multiple projects -  WAppBIU_Server and WebAPI.
This will enable the server side and the ranking page.

# Using the client side with the server
In addition, to check the integration with the client (REACT) please go to : https://github.com/danielkarl888/WAppBIU/tree/serverBranchKarl
On this link, the running instructions are the same as the readme file in this link.
**Please clone the brance named "serverBranchKarl".** this branch is adapted to the server.

# SignalR
To use the signalr, please install **On the client folder** with the command "npm i --save @microsoft/signalr"
This feature  only works for LIVE messages.
When adding a contact with other user , please relogin for both of them in order to make the chat updated.
(this is because the requirement is only for messages) 


# Pre-Registered Users
in order to make your work easier, we put the users david and raz on the server.
We put some contacts and messages for each of them. 
their passwords is their names + 1 (for example, david has the password david1).

# Server adderess
The address for the webAPI is "localhost:5030". Use this address to interact with the server.
All Server's data is located on this address.

# Client adderess
Please use the address http://localhost:3000 for the react web app.
# Test of WebAPI
To check our API with Swagger, please register with our **/api/Users/Register** and afterwards with  **/api/Users/Login**.
to use all **/api/contacts/.../** please enter at the user parameter the logged-in user in order to check his data with the api.
Ofcourse, the client side uses all this APIs.









