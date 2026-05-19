# 2c.SIMULATING ARP /RARP PROTOCOLS
## AIM
To write a python program for simulating ARP protocols using TCP.
## ALGORITHM:
## Client:
1. Start the program
2. Using socket connection is established between client and server.
3. Get the IP address to be converted into MAC address.
4. Send this IP address to server.
5. Server returns the MAC address to client.
## Server:
1. Start the program
2. Accept the socket which is created by the client.
3. Server maintains the table in which IP and corresponding MAC addresses are
stored.
4. Read the IP address which is send by the client.
5. Map the IP address with its MAC address and return the MAC address to client.
P



## PROGRAM - RARP

SERVER

<img width="677" height="296" alt="image" src="https://github.com/user-attachments/assets/5c7d6600-8eb8-4bd2-bedf-dd6154acff10" />

CLIENT

<img width="513" height="175" alt="image" src="https://github.com/user-attachments/assets/b0cc5273-50f1-4013-a205-9deccbc6ba1f" />

## OUPUT -RARP

SERVER


<img width="1017" height="261" alt="image" src="https://github.com/user-attachments/assets/6f011e7d-9ac9-4eb2-a5d6-917c694a126b" />


CLIENT

<img width="812" height="272" alt="image" src="https://github.com/user-attachments/assets/486cce3b-b881-498e-8a88-4efd7ac2b0e1" />


## RESULT
Thus, the python program for simulating ARP protocols using TCP was successfully 
executed.
