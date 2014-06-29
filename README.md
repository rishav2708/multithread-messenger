multithread-messenger
=====================

Multithreaded Messenger (Implementation of Group Chat)

This is multithreaded chat UI based where one or more clients can participate in one group chat.
It is simple implementation of socket programming and synchronizing multithreads.
The only problem due to which multithreading concept has been introduced is the problem of abrupt logging out of the user.
Java manages the session abruption well... :)

This follows simple TCP/IP and UDP/IP protocols to transfer messages through the sockets and stored in the buffer for a given interval of time.

The concept is same as of Ip mesanger.

Well, the code requires quite an improvement with the priorities of the user.

This is a new kind of idea where we will try to bring the messenger to the next level where one can talk to another person based on the
priorities they hold in each other's life.

This can be simply said that if for B priority of A is higher than of C , through the program we can make sure that chat between A<->B gets a
higher privilege... :P

This can be done by reseting the Java MIN_PRIORITY,MAX_PRIORITY and NORMAL_PRIORITY of the vectors of Threads.. 

We are trying to implement the same.. (Following the ideas of Thread Scheduling and Deadlock avoidance)

Installation:
 >simple java program type installation
 
 
 
