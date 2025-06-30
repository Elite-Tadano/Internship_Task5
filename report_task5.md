# Task 5 Report: Network Traffic Capture & Protocol Analysis using Wireshark

## Objective
- To perform live packet capture using Wireshark, analyze network traffic, and identify at least three different types of network protocols.

## Environment Setup
**Tool Used**: Wireshark (Free and open-source)

**System**: Windows 10 / Ubuntu

**Interface Used**: Wi-Fi (active connection)

## Procedure
1. Started Wireshark and selected the Wi-Fi interface.
2. Began live capture by clicking the green shark icon.
3. Generated traffic:
- Browsed to https://www.google.com
- Executed ping google.com in the terminal.
4. Stopped capture after approximately 60 seconds.
5. Applied filters in Wireshark:
- tcp to see TCP handshake and data flow
- http to observe HTTP GET/POST traffic
- dns to capture domain lookup queries and responses
6. Analyzed the captured packets using the protocol and info columns.

## Protocols Observed
1. TCP (Transmission Control Protocol)
- Purpose: Reliable, connection-oriented transport layer protocol.
- Observation: 3-way handshake observed (SYN, SYN-ACK, ACK). TCP streams used for HTTP communication.

2. HTTP (HyperText Transfer Protocol)
- Purpose: Application-layer protocol for fetching web pages.
- Observation: GET and 200 OK responses captured while loading Google.

3. DNS (Domain Name System)
- Purpose: Translates domain names (e.g., google.com) to IP addresses.
- Observation: A query for google.com and the corresponding IP response observed.

## Key Filters Used

`tcp`	: To capture TCP-level communications
`http` : To analyze web requests and responses
`dns` :	To monitor domain name resolution

## Conclusion / Learning Outcome
- This task provided hands-on experience in:
- Setting up Wireshark for live traffic capture.
- Understanding the behavior of common protocols in real-time.
- Using filters to narrow down traffic views.
- Enhancing protocol awareness and analysis skills useful for troubleshooting and security monitoring.

