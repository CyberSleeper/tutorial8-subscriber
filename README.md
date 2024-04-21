# What is amqp?
AMQP (Advanced Message Queuing Protocol) is a protocol for message-oriented middleware. The defining features of AMQP are message orientation, queuing, routing (including point-to-point and publish-and-subscribe), reliability and security. In our code, we use the AMQP protocol to send and receive messages between the client and the server.

# what it means? guest:guest@localhost:5672, what is the first quest, and what is the second guest, and what is localhost:5672 is for? 
This is commonly known as connection string. In AMQP, the common format for the connection string is `username:password@host:port`.Hence, the first `guest` is the username and the second `guest` is the password. The `localhost:5672` is the host and port number. The default port number for AMQP is 5672.