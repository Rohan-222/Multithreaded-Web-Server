# Multithreaded-Web-Server


A scalable web server implemented in Java to handle multiple concurrent client requests using multithreading. The server is built to adhere to HTTP/1.0 standards and supports serving static files efficiently.
Features

    Multithreading: Handles multiple client requests simultaneously using a thread pool (ExecutorService).
    Static File Hosting: Serves static files (HTML, CSS, JS) based on HTTP GET requests.
    Concurrency Management: Efficient thread pooling to reduce overhead and optimize server performance.
    Graceful Shutdown: Ensures all threads finish their tasks before shutting down the server.

Technologies Used

    Java: Core programming language.
    Socket Programming: For network communication (ServerSocket, Socket).
    Multithreading: ExecutorService for managing threads.
    HTTP Protocol: Implements basic HTTP/1.0 standards for serving files.
    File I/O: Java I/O for file handling and serving static content.

Performance Testing

The server has been performance-tested using Apache JMeter to evaluate its efficiency under various loads:

    Load Testing: Simulated multiple concurrent client requests to assess responsiveness and throughput.
    Stress Testing: Evaluated the server’s stability under extreme load conditions.
    Response Time Analysis: Analyzed latency and average response times for varying numbers of concurrent users.
    Thread Pool Optimization: Measured the performance impact of varying thread pool sizes.
