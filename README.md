# Insident-Reposrt
Cyber Security Incident Report for Travel Agency 

Section 1: Identify the type of attack that may have caused this
network interruption
  1)One potential explanation for the website's connection timeout error message is: connection timeout error message in your browser which is DOS attack
  2)The logs show that: large number of SYN requests
  3)This event could be: SYN Flood Attack which is type of DOS attack

Section 2: Explain how the attack is causing the website to malfunction
When website visitors try to establish a connection with the web server, a three-way
handshake occurs using the TCP protocol. Explain the three steps of the handshake:
  1.First the SYN request goes to server.  
  2.Second SYN ACK responce to source that accepted the source request.
  3.ACK from the source to server for persmission to connect.

Explain what happens when a malicious actor sends a large number of SYN packets all at
once: The server gets hanged or stop responding to the source request. 

Explain what the logs indicate and how that affects the server: Server gives the error msg that connection timeout
