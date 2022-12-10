# Computer-Networks-Project-Chatroom

A chatroom built in C++ using the concepts of socket programming and multi-threading. It supports chatting among multiple clients. By using socket programming on AWS platform, Interaction between admin and client can be effectively carried out, means the clients can chat with the admin or can discuss any query.

Steps to run-
firstly run the server using terminal write-> g++ chatserver.cpp -lpthread -o server
then write ./server

after running server we have to run as many client as we want so for that write-> g++ chatclient.cpp -lpthread -o client
then write ./client

now our chatroom is in working condition and start chatting.
