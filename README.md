# linux-cmd
1. IFCONFIG COMMAND
<br> This command is for finding your IP address and default gateway.
<br>![Capture](https://user-images.githubusercontent.com/44020138/106436795-607a5a00-6429-11eb-8331-b2ed9f6c507d.JPG)

<br>2. ARP COMMAND
<br> This command is for showing the address resolution cache. Arp command must be used with a command line switch arp -a is the most common.
<br>![Capture](https://user-images.githubusercontent.com/44020138/106574866-48b9d900-64f0-11eb-8e30-4b9b86a718f6.JPG)

<br>3. NSLOOKUP
<br> To use a specific DNS server for the query, add the server name or IP address to the end of the command. 
<br>![Capture](https://user-images.githubusercontent.com/44020138/106575494-01801800-64f1-11eb-98b8-1f04b0fecf40.JPG)
<br> From this, we can see that example.com is currently pointing to IP address 93.184.216.34. We can also see that DNS server example.com was used for the query.
<br>4. NETSTAT
<br>![Capture](https://user-images.githubusercontent.com/44020138/106576548-2032de80-64f2-11eb-8e37-38d14d1457eb.JPG)
<br>The output mean:
<br>Recv-Q
<br>How many bytes the receiver has in their buffer. This buffer not yet copied by the user program.
<br>Send-Q
<br>Indicate that amount of bytes sent by the remote host.
<br>Local Address
<br>The port number and address of the local socket. Unless the -n argument is passed the address is translated to its FQDA and port number is translated to its corresponding service.
<br>Foreign Address
<br>Address and port number of remote host. (See local address)
<br>State
<br>The current state of the socket.
<br>Examples:
<br>*netstat -a
<br>  -list all ports
<br>*netstat -at
<br> -list all TCP ports
<br>*netstat -au
<br>  -List all UDP ports
<br>*netstat -l 
<br> -List only listening ports
<br>*netstat -s
<br>  -Show statistics for all ports.
