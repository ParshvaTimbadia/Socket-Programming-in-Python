# Socket-Programming-in-Python

SOCKET programming is the way to communicate bwtween two nodes. Nodes can be anything either client or server. However, communication can be established between a client and a server or client to client as well. One socket(node) listens on a particular port at an IP, while other socket reaches out to the other to form a connection. Server forms the listener socket while client reaches out to the server.
Although it is possible to create a connection between two client system, it is always better to create a sever as a communicator for privacy and security reasons. As of now, I am creating sever and client within one system and hence the code which I am uploading will need two instances to work. You can later try connecting using the external systems you just need to change the IP address.

So lets begin with thw Socket Programming with the help of Python. 

Sources Referred:

https://docs.python.org/3/library/socket.html
https://dzone.com/articles/python-thread-part-1
https://realpython.com/python-sockets/#:~:text=accept()%20blocks%20and%20waits,flowinfo%2C%20scopeid)%20for%20IPv6.
https://www.geeksforgeeks.org/socket-programming-python/#:~:text=Socket%20programming%20is%20a%20way,reaches%20out%20to%20the%20server.
https://www.studytonight.com/network-programming-in-python/socket-methods
https://www.tutorialspoint.com/python/python_multithreading.htm
