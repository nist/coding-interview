# Web

**1. What is a web server ? Give some examples.**
A web server allow to serve HTML page and application.
Apache HTTP and NGINX are both popular web servers.
**2. What is the difference between TCP and UDP ?**
Both are protocol to exchange data between two computers.
*T*ransport *P*rotocol respond to a strict standard that enforce error handling.
*U*ser *D*atagram *P*rotocol implement a less strict protocol, in which paquet can be loss.
UDP is faster than TCP.
**3. Where are the logs of a web server ?**
For Apache HTTPD usually in `/var/log/apache2`
**4. How to secure a connection between a client and a server ?**
Ẁith a secure certificate provided by an official source and used to encrypt the connection.
**5. What difference between HTTP/2 and HTTP/3 ?**
The goal of the version 3 is to provide a fast, reliable and secure connection between different kind of devices. 
Version 2 use TLS over TCP.
Version 3 use QUIC over UDP.
**6. What is a webSocket ?**
A WebSocket is a bidirectional, realtime connection in full duplex between a client and a server.

**7. What is a DDoS ? How to prevent or stop one ?**
A *D*istributed *D*enial *o*f *S*ervice, a type of attack on a server that came from many clients and ask for a service, which flood the server.
There's tools to monitor and mitigate this kind of attack.
**8. What is the current version of the HTML standard ?**
There's no more version since the standard evolve continually.
**9. What actions are supported in http ?**
- GET
- POST
- PUT
- DELETE
- PATCH
**10. What differences between web 1.0, 2.0 and 3.0 ?**
1.0 : Website are mostly static.
2.0 : Website evolve to be similar to applications (interactive) and social interaction.
3.0 : THe will to take back the control of the web from the grasp of Big Tech, by using decentralized data and cryptocurrencies.
