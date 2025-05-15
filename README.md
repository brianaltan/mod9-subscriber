# mod9-subscriber

1. **What is AMQP?**

    AMQP stands for Advanced Message Queuing Protocol. It is a network protocol used to send messages between applications and systems. AMQP is commonly used for communication between programs via message brokers like RabbitMQ, which we will be using in this module.

2. **What does guest:guest@localhost:5672 mean?**

    This is a connection string used to connect to an AMQP server (RabbitMQ in our case).

    The format follows this pattern:
    ``amqp://username:password@host:port``

    Breaking it down:
    - The first "guest" is the username used to authenticate with the AMQP server (default credential)
    - The second "guest" is the password for authentication (default credential)
    - "localhost" indicates that the AMQP broker is running on our local machine
    - "5672" is the standard port number on which the AMQP service listens for connections