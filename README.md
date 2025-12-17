# wireshark-network-capture-task
i have done a network capture using wireshark. this is my report on it and gained hands-on packet analysis skills and protocol awareness
 Wireshark Network Capture and Analysis (Windows)
🎯 Objective
To perform live packet capture using Wireshark, analyze different network protocols, and summarize findings for network troubleshooting and monitoring.

⚙️ Steps Performed
1. Install Wireshark
Download Wireshark from https://www.wireshark.org/download.html
Install it along with Npcap (required for packet capture).
2. Start Capturing on Your Active Network Interface
Open Wireshark.
Select your active network interface (Wi-Fi or Ethernet) that shows live traffic.
Click the blue shark fin (▶️) icon to begin capturing packets.
3. Browse a Website or Ping a Server to Generate Traffic
Visit websites like https://www.google.com or https://www.wikipedia.org
Or open Command Prompt and run:
ping google.com
This generates traffic for DNS, TCP, ICMP, and HTTP/HTTPS protocols.

4. Stop Capture After a Minute
Click the red square stop button (⏹️) on the toolbar to stop capturing.
You can now analyze the captured packets.
5. Filter Captured Packets by Protocol
Use Wireshark’s Display Filter bar to show specific traffic.

Protocol	Filter Command
HTTP	http
DNS	dns
TCP	tcp
ICMP	icmp
Type the filter and press Enter to view only that protocol’s packets.

6. Identify at Least 3 Different Protocols
During the capture, you should observe multiple protocols such as:

DNS – Domain name queries and responses
TCP/UDP – Data transmission
HTTP/HTTPS – Web communication
ICMP – Ping packets (if you used ping)
7. Export the Capture as a .pcap File
Go to File → Save As...
Save the capture as network_capture.pcap
8. Summarize Findings and Packet Details
Summary Example: During the Wireshark capture, several protocols were detected including DNS, TCP, and HTTP traffic.

DNS packets resolved domain names like google.com.
TCP packets established connections and transferred data.
HTTP packets showed website requests and responses.
The capture confirmed normal browsing behavior with successful communication between client and servers.
Total Packets Captured: ~1000
Active Protocols: DNS, TCP, HTTP, ICMP
Capture File: network_capture.pcap

📸 Screenshot:
Screenshot 2025-10-27 105255 Screenshot 2025-10-27 105339 Screenshot 2025-10-27 105449 Screenshot 2025-10-27 105514 Screenshot 2025-10-27 105555 Screenshot 2025-10-27 105612 Screenshot 2025-10-27 105633

📋 Summary Table
Step	Action	Output
1	Install Wireshark	Application installed successfully
2	Start Capture	Live packets displayed
3	Generate Traffic	Packets captured during browsing/ping
4	Stop Capture	Capture saved for analysis
5	Apply Filters	Displayed specific protocol traffic
6	Identify Protocols	Found DNS, TCP, HTTP
7	Export File	.pcap file saved
8	Summary	Documented findings
✅ Author
Name: m.lalithapriya
Task: Internship Task – Wireshark Network Capture
Platform: Windows
Date: december 2025 Screenshot 2025-10-27 105633 Screenshot 2025-10-27 105644 Screenshot 2025-10-27 110004
