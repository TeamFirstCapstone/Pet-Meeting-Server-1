# Pet-Meeting-Server-1




# Built With

 * []() Node.js
 * []() Redis 
 * []() MySQL
 
 https://user-images.githubusercontent.com/46518769/103146854-7180dd00-4792-11eb-83aa-80ebf5184bac.png
 
 
 Web Socket
Web Socket technology is necessary for real-time chatting systems on our Pet-Meeting service. Web socket is a computer communications protocol,
providing full-duplex communication channels over a single TCP connection. WebSocket and HTTP are all located at layer 5 in the OSI model and depend
on TCP at layer 4. However WebSocket, defined on RFC 6455, is designed to work over HTTP ports 443 and 80 as well as to support HTTP proxies and intermediaries.

Socket.io enables real-time, bidirectional and event-based communication. It works on every platform, browser or device, focusing equally on reliability and speed. 
Socket.IO is not a WebSocket implementation, although it can communicate with each other. Socket.IO provides powerful reliability which can support proxies and load 
balancers. And if there is some fault while connecting, Socket.IO makes auto-reconnection and periodic disconnection detection is supported. And also to 
create separation of concerns, it allows us to create several namespaces to separate communication channels but will share the same underlying 
connection. Web socket technology is necessary for real-time chatting systems on our pet platform.


Master and Slave
Master and slave or Master/Slave is a model of asymmetric communication or control where one device or process controls one or more other devices or processes and serves as their communication hub.  We concern only master/slave models of Database, especially MySQL and Redis. Master/Slave is one solution of replication to prevent some unexpected faults of the data center. Master keeps the replica updated by sending a stream of commands to the replica, in order to replicate the effects on the dataset happening in the master side. When link between the master and the replica breaks, for network issues or because a timeout is sensed in the master or the replica, the replica reconnects and attempts to proceed with a partial resynchronization. When a partial resynchronization is not possible, the replica will ask for a full resynchronization. This will involve a more complex process in which the master needs to create a snapshot of all its data, send it to the replica, and then continue sending the stream of commands as the dataset changes

