<h1>Incident Response</h1>


<h2>Description</h2>
In this project, I created an incident report base on one of the Google Cybersecurity Certificate example scenarios: 

You are a cybersecurity analyst working at a company that specializes in providing IT services for clients. Several customers of clients reported that they were not able to access the client company website www.yummyrecipesforme.com, and saw the error “destination port unreachable” after waiting for the page to load. 

You are tasked with analyzing the situation and determining which network protocol was affected during this incident. To start, you attempt to visit the website and you also receive the error “destination port unreachable.” To troubleshoot the issue, you load your network analyzer tool, tcpdump, and attempt to load the webpage again. To load the webpage, your browser sends a query to a DNS server via the UDP protocol to retrieve the IP address for the website's domain name; this is part of the DNS protocol. Your browser then uses this IP address as the destination IP for sending an HTTPS request to the web server to display the webpage  The analyzer shows that when you send UDP packets to the DNS server, you receive ICMP packets containing the error message: “udp port 53 unreachable.” 
<br />


<h2>Utilities Used</h2>

- <b>Google Docs</b>

<h2>Project walk-through:</h2>

<p align="center">
ICMP packets recieved during the packet sniffing process: <br/>
<img src="https://i.imgur.com/aEabzxs.png"/>
<br />
<br />
Incident response:  <br/>
<img src="https://i.imgur.com/FKe5vcB.png"/>
<br />
