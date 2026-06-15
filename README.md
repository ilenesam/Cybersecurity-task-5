# Cybersecurity-task-5
# Task 5 - Capture and Analyze Network Traffic Using Wireshark

## Objective

Capture live network packets and identify basic protocols and traffic types.

## Tool Used

- Wireshark

## Procedure

1. Installed Wireshark and Npcap.
2. Started packet capture on the active network interface.
3. Generated traffic by:
   - Browsing websites
   - Running ping commands
4. Captured packets for approximately one minute.
5. Applied protocol filters.
6. Analyzed network traffic.
7. Exported capture as a .pcapng file.

## Protocols Identified

### DNS
Used for translating domain names into IP addresses.

### TCP
Provides reliable communication between devices.

### ICMP
Used for network diagnostics and ping requests.

## Findings

- DNS queries were observed while accessing websites.
- TCP traffic was responsible for web communication.
- ICMP packets appeared during ping operations.
- Various source and destination IP addresses were identified.

## Conclusion

Wireshark provides detailed visibility into network traffic and is useful for troubleshooting, monitoring, and security analysis.
