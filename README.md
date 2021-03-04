https://www.google.com/search?q=Socket+IO+in+Spring+Boot&sa=X&ved=2ahUKEwjMypPMgpbvAhUCzTgGHQauC8cQ1QIwDXoECA4QAQ&biw=1536&bih=754

https://stackoverflow.com/questions/57505589/can-i-use-socket-io-with-spring-boot

https://stackoverflow.com/questions/15568700/best-java-server-implementation-for-socket-io/16711894#16711894

# An example of real-time chat application 

Built with 
- [netty-socketio 1.7.17](https://github.com/mrniko/netty-socketio) 
- Spring Boot 2.1.1.RELEASE
- socket.io-client 2.2.0

In this example, `SocketIONamespace` is used for declaring modules. 

This example project is inspired by the following projects.
- https://github.com/Heit/netty-socketio-spring
- https://github.com/mrniko/netty-socketio-demo

# Usage

## Server end

- Run server by command `mvn spring-boot:run`   
- Or build single executable jar file with `mvn package` and un single jar `java -jar rt-server.jar`

## Client end

- Put the `/client` directory under an HTTP server. Then open it from the browser after starting the server side.

# License

MIT
