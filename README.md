# Advanced Data Engineering

## Key Terms

- `Queue`: A place where items of work are stored and managed. Items of work represent units of tasks or actions that need to be processed.

- `First In, First Out (FIFO)`: A pattern of behavior for queues where the first item added to the queue is the first one to be processed.

- `Last In, First Out (LILO)`: A pattern of behavior for queues where the last item added to thequeue is the first one to be processed.

- `Producer`: The entity responsible for generating and adding units of work to the queue.

- `Consumer`: The entity responsible for processing and removing units of work from the queue.

- `Broker/Message broker`: A separate process used to connect Python applications to message queues such as RabbitMQ.

- `Celery`: A middleman package in Python that allows producing items of work in Python and putting them somewhere else, such as RabbitMQ.

- `AMQP`: Advanced Message Queuing Protocol, a protocol for messaging middleware used by RabbitMQ.

- `Task queue`: Represents a specific type of message queue designed to handle tasks or units of work.

- `Concurrency`: The ability for multiple operations to execute simultaneously.

- `Serialization`: The process of converting complex data types into simpler formats for storage or transmission.

- `Image processing`: A use case for queues involving resizing images and creating down samples at large scales.

- `Publish/Subscribe (Pub/Sub)`: An architectural pattern used in message queuing systems allowing multiple entities to communicate by publishing messages to a queue and subscribing to receive those messages.

- `Request-Reply Pattern`: A communication model between two parties where one party sends a request and expects a response from the second party.

- `Flask`: A lightweight web framework for Python used for building web applications.

- `requirements.txt`: A file used in Python to declare necessary libraries and packages required for running a specific application or program.

- `Units of work`: Represent individual tasks or actions that need to be processed. These could be data, sending emails, or any other type of action

