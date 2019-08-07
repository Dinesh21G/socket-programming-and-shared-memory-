# socket-programming-and-shared-memory-
Ethernet adapter and shared memory stress


Generate a random string on shared memory and verify with loopbacked network adapters, 

server and client model to run stress on network loopbacked ethernet adapters

./ser -h

Usage : ./ser [-i ip][-p port][-b buffer size(Bytes.)]
 -i - IP address to bind       default : 0.0.0.0
 -p - port to listen           default : 7373
 -b - Buffer size (in Bytes)   default : 1024
 -k - Key for shared memory    default : 9876

 ./cli -h

Usage : ./cli [-i ip][-p port][-b buffer size(Bytes.)]
 -i - IP address to bind       default : 0.0.0.0
 -p - port to listen           default : 7373
 -b - Buffer size (in Bytes)   default : 1024
 -k - Key for shared memory    default : 9876

