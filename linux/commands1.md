
touch <file> create an empty file
cat <file> view file content
nano <file> edit a file
ps aux - shows all running process
less <file> view large files page by page
df -h check disk space usages
du -sh <dir> check directory size
find <dir> name <file> search for a file
ip a show network interface and ip address
ping <host> test network connection
curl <url> fetch data from a url
wget <url>downloads files
whoami- show current user
who- show logged in user
sudo <command> run command as superuser
adduser <user>- add new user
passwd <user> -change user passworld
uptime- show system uptime
free -h -show memory usages
dmesg- view system log
gzip<file> -compress file
gunzip <file.gz> decompress file
apt update @@ apt upgrade- update system
apt install <package> install a package
apt remove <package> remove a package
alias ll= "ls -la"- create ashortcut command
history- show command history
clear- clear the terminal
exit- log out from the session
1. #Types of Computer Networks
a) Based on Coverage Area
LAN (Local Area Network)

Covers a small area (home, office, school).
High-speed data transfer.
Example: Wi-Fi network in a house.
WAN (Wide Area Network)

Covers large geographic areas (cities, countries).
Slower than LAN due to long-distance communication.
Example: The internet.
MAN (Metropolitan Area Network)

Covers a city or campus.
Faster than WAN but limited to a city-scale.
Example: Government/corporate network spanning a city.
PAN (Personal Area Network)

Used for personal devices (Bluetooth, mobile hotspot).
Example: A smartwatch connected to a phone via Bluetooth.
CAN (Campus Area Network)

Connects multiple LANs within a university or business campus.
b) Based on Architecture
Client-Server Network

A centralized server manages resources and requests from client devices.
Example: Web applications where clients request data from a web server.
Peer-to-Peer (P2P) Network

Devices communicate directly without a centralized server.
Example: File sharing networks like BitTorrent.
2. Network Components
a) Hardware Devices
Router – Directs traffic between different networks and connects to the internet.
Switch – Connects multiple devices in a LAN and efficiently manages data transfer.
Hub – Broadcasts data to all devices (less efficient than a switch).
Modem – Converts digital signals into analog for internet access and vice versa.
Access Point – Extends Wi-Fi network coverage.
Firewall – Security system that filters and monitors network traffic.
b) Software & Protocols
Operating Systems (OS) – Windows, Linux, or macOS handle network communication.
Protocols – Rules for communication between devices (TCP/IP, HTTP, FTP, DNS, etc.).
3. Network Protocols
IP (Internet Protocol) – Assigns unique addresses to devices for communication.
TCP (Transmission Control Protocol) – Ensures reliable data transmission.
UDP (User Datagram Protocol) – Faster but does not guarantee reliability.
HTTP/HTTPS (HyperText Transfer Protocol) – Used for web browsing.
FTP (File Transfer Protocol) – Transfers files between devices.
DNS (Domain Name System) – Translates domain names (e.g., google.com) into IP addresses.
SMTP/POP3/IMAP – Email communication protocols.
NAT (Network Address Translation) – Converts private IPs to public IPs.
4. IP Addressing
a) IPv4 vs IPv6
IPv4 – 32-bit address (e.g., 192.168.1.1), limited availability.
IPv6 – 128-bit address (e.g., 2001:db8::ff00:42:8329), supports more devices.
b) Public vs Private IP
Public IP – Globally unique, used to communicate over the internet.
Private IP – Used within local networks (e.g., 192.168.x.x, 10.x.x.x).
c) Static vs Dynamic IP
Static IP – Fixed and manually assigned (good for servers).
Dynamic IP – Assigned by DHCP and changes periodically.
6. OSI Model (7 Layers of Networking)
Physical Layer – Cables, wireless signals, network interfaces.
Data Link Layer – MAC addresses, switches, error detection.
Network Layer – IP addressing, routing (handled by routers).
Transport Layer – TCP/UDP, ensures reliable communication.
Session Layer – Manages sessions (logins, data streams).
Presentation Layer – Encryption, data formatting (SSL/TLS).
Application Layer – User applications (web browsers, email clients).
6.  Basic Networking Commands
ping <IP> – Checks if a device is reachable.
ipconfig / ifconfig – Displays IP and network settings.
tracert <IP> – Shows the path packets take to a destination.
nslookup <domain> – Resolves domain names to IPs.
netstat – Displays active network connections.
7. Network Security
Firewalls – Block unauthorized access to a network.
Encryption – Protects data using cryptographic methods (SSL/TLS, AES).
VPN (Virtual Private Network) – Encrypts data for secure remote access.
Antivirus & IDS/IPS – Detects and prevents network attacks.
Subnet: A subdivision of an IP network that helps organize and manage network traffic. It allows for better control over network resources and improves security.
CIDR (Classless Inter-Domain Routing): A method for allocating IP addresses and routing, represented as x.x.x.x/n, where n defines the number of bits used for the network prefix (e.g., 192.168.1.0/24).
Network Interface: A virtual or physical adapter that connects a device to a network, enabling communication. Examples include Ethernet adapters and AWS Elastic Network Interfaces (ENIs).
Private IP: An IP address assigned to a device within a private network. It is not accessible from the internet and is used for internal communication (e.g., 192.168.1.10).
Public IP: An IP address assigned to a device that is accessible over the internet. It is unique globally and allows external communication (e.g., 203.0.113.5).