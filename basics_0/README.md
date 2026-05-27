# holbertonschool-network
Networking


While the full list of ports should not be memorized, it is important to know the most used ports, let's start by remembering 3 of them:

22 for SSH
80 for HTTP
443 for HTTPS


A listening port is a network port that a service or application has "bound" to, remaining open to wait for and accept incoming connection requests or data from other nodes

A bash script to show listening sockets begins with #!/usr/bin/env bash and utilizes the netstat utility to display all active ports and communication endpoints

A bash script using #!/usr/bin/env bash and the netstat -p command (note: the -p flag is not specified in the sources) will display the PID and name of the program for each network socket