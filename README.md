# SocketsCA3

The client server application consists of two files; server.js and index.html.
To run the application the server.js file is called from the Node command line
$ node server.js
The application demonstrates the setting up of a WebSockets connection between 
a client Browser and a node server. The buttons in the browser interface each have
a connection with the server. When the button is clicked the server increments its 
counter and sends the incremented number of clicks back to the browser which
then displays the updated number.
