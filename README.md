# Network-port-scanner
1️⃣👉 This Python code is a network port scanner that scans a target machine for open ports.

2️⃣👉 The code begins by importing the necessary modules: sys, socket, and datetime.

3️⃣👉 The IP address of the target machine is defined using the socket module's gethostbyname() function. The IP address is obtained from the command line argument passed to the script.

4️⃣👉 A banner is printed to the console that indicates the target IP address and the time at which the scan was initiated.

5️⃣👉 The code then attempts to scan for open ports on the target machine by looping through a range of port numbers.

6️⃣👉 For each port, the code creates a new socket object and attempts to connect to the target IP address on that port using the socket's connect_ex() method.

7️⃣👉 If the connect_ex() method returns 0, it means that the port is open and the code prints a message to the console indicating that the port is open.

8️⃣👉 After checking all ports, the socket is closed and the program exits.

9️⃣👉 The code also includes exception handling for keyboard interrupt (i.e. when the user presses Ctrl + C to exit the program), hostname resolution error, and socket error.

🔟👉 Overall, the code is a simple but effective way to scan a target machine for open ports and can be useful for information gathering in various contexts, such as penetration testing or network security auditing.
