# Echo Server using Netty

## Description
This is a simple Echo Server implemented using Netty that receives a message from a client and echoes it back.

## Requirements
- Java 8 or higher
- Maven

## Setup
1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/echo-server.git
    cd echo-server
    ```

2. Build the project using Maven:
    ```sh
    mvn clean install
    ```

## Running the Server
To run the server, use the following command:
```sh
java -cp target/echo-server-1.0-SNAPSHOT.jar com.example.EchoServer [port]
