# The HTTP Request Lifecycle
## HTTP is a TCP-based application layer protocol that uses a client-server communication model to which requests are sent to them by clients and answered by the third party.

********************************************************

## Local Processing
* the browser is response about made  the request , extracting the request to a parts like "schema", optional port number, resource path, and query strings (as we took in 301 course).

**|http|://|www.facebook.com||:5000||/mainpage||?query=param&query2=param2|**
>* Http or Https : is the protocol .
>* www.facebook : is the host address .
>* 5000 : is the port number.
>* /mainpage : path it take us to specific page .
>* qurey : its the parameters that we are using to send the data to our ApI server or to the 3rd party API .

## Resolve an IP
* in this step the browser is trying to send the request to the  DNS server that respons on finding the addres  for the webpage that is in your req if this dns find the address it will ruter the response if not it will send the request again to another DNS server until the address is found(the requesting client now has a target IP).
## Establish a TCP Connection
* now we had the IP address so we can send HTTP req , but we need first to open TCP(transport layer protocol ) connection.
and to open TCP connection we need to use  a three-way handshake(its way to connect the client with the server and have many steps[steps](https://www.sciencedirect.com/topics/computer-science/three-way-handshake)).



## ![img](https://ars.els-cdn.com/content/image/3-s2.0-B9781597499613000030-f03-08-9781597499613.jpg)

* now after that we have  connection between both the client and server.
## Send an HTTP Request
* we already had the TCP connection and the IP address so we can in this step send the HTTP request (the req line as shown and defined in the step 1).
* after sending the request the server will reseve this request the server will find the resources that requested and make the response for the req (as we took in 301) and the data will deliver to the client.

## Tearing Down and Cleaning Up
* in this step after reseveing all the data we requested the Tcp connection will be ended .
* after that your computer will start Dealing with this data and render this data or sending a new request again to repeat the same process again and again ......  
.
 