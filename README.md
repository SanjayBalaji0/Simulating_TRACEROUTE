# Simulating_TRACEROUTE
## AIM
To write the python program for simulating Traceroute command 
## ALGORITHM
1. Start the program. 
2. Get the frame size from the user. 
3. To create the frame based on the user request. 
4. To send frames to server from the client side. 
5. If your frames reach the server, it will send ACK signal to client otherwise it will send NACK signal to client. 
6. Stop the program

## PROGRAM
```
from scapy.all import* 
target = ["www.google.com"] 
result, unans = traceroute(target,maxttl=32) 
print(result,unans) 
```
## OUTPUT
![image](https://github.com/SanjayBalaji0/Simulating_TRACEROUTE/assets/145533553/1abb02f7-32ff-4752-b388-7e099be3008d)
![image](https://github.com/SanjayBalaji0/Simulating_TRACEROUTE/assets/145533553/844295d7-513c-4530-8f1b-b0b35551cfcd)

## RESULT
Thus, the python program for simulating Traceroute command was successfully executed.
