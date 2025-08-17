# Cybersecurity-Incident-response-report
Incident response case study analyzing a DNS service outage and mitigation steps
 The Incident is: 
 You are a cybersecurity analyst working at a company that specializes in providing IT services for clients. Several customers of clients reported that they were not able to access the client company website www.yummyrecipesforme.com, and saw the error “destination port unreachable” after waiting for the page to load. 
You are tasked with analyzing the situation and determining which network protocol was affected during this incident. To start, you attempt to visit the website and you also receive the error “destination port unreachable.” To troubleshoot the issue, you load your network analyzer tool, tcpdump, and attempt to load the webpage again. To load the webpage, your browser sends a query to a DNS server via the UDP protocol to retrieve the IP address for the website's domain name; this is part of the DNS protocol. Your browser then uses this IP address as the destination IP for sending an HTTPS request to the web server to display the webpage  The analyzer shows that when you send UDP packets to the DNS server, you receive ICMP packets containing the error message: “udp port 53 unreachable.
 Incident diagram:<img width="902" height="448" alt="image" src="https://github.com/user-attachments/assets/41459c3a-5c60-4813-b6fb-da384f651c4e" />

[incident response report.pdf](https://github.com/user-attachments/files/21822676/incident.response.report.pdf)
