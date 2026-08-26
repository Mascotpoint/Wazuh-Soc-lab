# Wireshark Network Traffic Analysis Lab

## Objective
The objective of this lab was to capture and analyze live network traffic using Wireshark and develop practical packet-analysis skills used by SOC analysts.

## Lab Environment
- Kali Linux
- Wireshark
- Oracle VirtualBox
- Ethernet interface: eth0

## Tasks Performed
1. Captured live network traffic using Wireshark.
2. Inspected TCP and HTTP packets.
3. Applied Wireshark display filters to isolate relevant traffic.
4. Examined HTTP request and response communication.
5. Used Follow TCP Stream to reconstruct a network conversation.
6. Identified an HTTP GET request to connectivity-check.ubuntu.com.
7. Observed the HTTP 204 No Content response.
8. Saved the packet capture as evidence for further analysis.

## Key Findings
The packet analysis demonstrated how client and server communication can be inspected at packet level.

The HTTP stream showed:
- HTTP GET request
- Host: connectivity-check.ubuntu.com
- HTTP/1.1 204 No Content response
- Connection termination after the response

## SOC Analyst Skills Practiced
- Network traffic monitoring
- Packet inspection
- TCP/IP analysis
- HTTP protocol analysis
- Wireshark filtering
- Follow TCP Stream analysis
- Evidence collection
- Network incident investigation

## Evidence
Supporting screenshots, packet capture files, and analysis notes are included in this lab folder.

## Conclusion
This lab provided hands-on experience using Wireshark to investigate network communications and understand how SOC analysts examine packet-level evidence during security investigations.
