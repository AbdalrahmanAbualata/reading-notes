# Spring and Sockets
## what is WebSocket : 
* WebSocket technology enables the opening of a connection or an open channel between the server and the client for all the duration of the session(all the time the clinet is connecting like chatting in fecebook ) and through it the two sides can exchange messages in both directions.
* meaning that the server can send whatever data it wants to the client without the  askinga permision for that, with processing and display this data is in real time without page reloading.
## Using WebSocket to build an interactive web application
## Procese
- we will create a server that recive data from a user (we send the data with the username )for the other side user (has unique username).
  
## Steps
1-we can use prebuilt repository in github for that .
2- Or follow this steps:
- Spring Initializr(like previous labs but we need to add Websocket Dependencie)
- Adding Dependencies(we need to add other dependencies because its not provided by spring initializr)
- Create a Resource Representation Class(her we need to create Stream Text-Oriented Messaging Protocol (STOMP) message service, we need to create a constructor for the the username who is sending the message and other constructor for the content of the massage(the massege at self) )
- Create a Message-handling Controller(her just we need to create a controller for handeling the process of mapping on the massage and resend the response)
- Configure Spring for STOMP messaging(we need to create a class to handle the configuration for the stomp massegees and  WebSocket )
- Create a Browser Client
- Make the Application Executable

## Test the service
- run the service then oper  http://localhost:8080  in browser and click the Connect button, after that write a name and send it the service well response to your req with (hello ,and the name you send).