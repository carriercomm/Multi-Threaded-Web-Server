Web_Server
==========

All files in the Source Files directory were written by Gabe Harms

The server.c file contains the main server loop, and is run continously until the server is turned off. The sockets
API in C is used in order to handle the HTTP requests. Multiple clients are be handled similtaneously using the server_thread.c files which initializes new threads each time a request comes in.
