# kali-vm-python-proxy
This is a starter proxy created to assist in a security project for my Computer Science degree. The purpose of it is manually sniffing and intercepting packets sent from the current machine to a seperate address. Usage strictly for security testing and risk management.

localhost: IP of local machine (no particular address suitable such as 0.0.0.0)
localport: An open local host that can data can be threaded to
remotehost: IP of remote machine OR website (depending on task)
remoteport: Port used by remote machine OR website (depending on task)
recieve_first: If true, allow sniff and manipulation of packets. Else, just sniff (testing)
