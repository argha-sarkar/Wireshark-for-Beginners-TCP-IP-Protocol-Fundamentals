# Wireshark-for-Beginners-TCP-IP-Protocol-Fundamentals
### Wireshark Overview
Wireshark is an open-source, widely-used network protocol analyzer that enables users to capture and inspect data traffic flowing through a network in real time. It gives a detailed view of the packets traveling through a network, allowing users to analyze, troubleshoot, and secure communications across the Internet. Wireshark is invaluable to network administrators, security professionals, developers, and anyone who wants to understand how network protocols work.

Wireshark is often used for network troubleshooting, as it helps identify and diagnose network issues like slow performance, misconfigurations, or connectivity problems. It is also used for protocol analysis, helping users break down complex network protocols and understand how data is transferred between devices on a network. In addition, Wireshark plays a key role in security auditing by helping detect potential vulnerabilities such as unsecured communications, misused ports, or protocol misuse. It is a great tool for learning and understanding networking concepts such as TCP/IP, HTTP, DNS, and more. Security professionals also use Wireshark for network forensics, investigating network traffic logs to find signs of malicious activity, data breaches, or unauthorized access.

### SSL/TLS in Wireshark
SSL (Secure Sockets Layer) and TLS (Transport Layer Security) are cryptographic protocols that provide secure communication over a network. These protocols encrypt data in transit, ensuring both privacy and data integrity. In Wireshark, SSL/TLS traffic is encrypted, so the actual contents of packets are not directly visible unless proper decryption methods are used. However, Wireshark can still be used to inspect details of SSL/TLS handshakes, view certificate information, and identify the cipher suites in use. For security professionals, this is crucial when troubleshooting SSL/TLS issues or ensuring secure communication practices.

In order to fully decrypt and analyze SSL/TLS traffic, Wireshark needs access to decryption keys, such as private keys or pre-master secrets. This allows for deeper inspection of encrypted communications, which is essential for ensuring security and compliance with privacy standards. Without the decryption keys, Wireshark will show the handshake details and the encryption methods being used, but the contents of the communication will remain unreadable.

### Wireshark on Linux Distributions
Wireshark is a cross-platform tool, but it is especially popular among users of Linux-based systems. This is largely because Linux distributions offer powerful networking support that works seamlessly with Wireshark. Linux provides access to low-level network interfaces and detailed packet capture capabilities, which enhance the effectiveness of Wireshark for analyzing network traffic.

Both Wireshark and many Linux distributions are open-source, making them an attractive option for users who prefer free and transparent software. Linux environments also provide robust security features, which are important for users involved in penetration testing or secure data analysis. Many Linux distributions, such as Kali Linux, are designed specifically for penetration testing, making them ideal for running Wireshark in security-sensitive contexts.

Additionally, Linux’s lightweight nature and the availability of various networking tools and utilities enable advanced users to fully customize their Wireshark experience. By integrating with tools like tcpdump or iptables, users can gain deeper insights into network traffic and leverage the full potential of Linux’s networking stack. This makes Wireshark on Linux a powerful and flexible choice for anyone involved in network analysis or security.

# Guided Wireshark Project: Packet Capture and Analysis

## Project Overview

In this guided project, you will use Wireshark to learn how to:

- Capture and save packets on a physical wired network.
- Create a display filter to observe TCP/IP packets on a specific port.
- Observe HTTP and HTTPS TCP/IP protocols.
- Identify the TCP/IP protocol stack.

## Learning Objectives

By the end of this project, you will be able to:

- Capture and save packets on a physical wired network using Wireshark.
- Use Wireshark to observe the Internet Layer of the TCP/IP model.
- Use Wireshark to observe the Transport Layer of the TCP/IP model.
- Use Wireshark to analyze the HTTP Application Layer of the TCP/IP protocol.
- Use Wireshark to analyze the HTTPS Application Layer of the TCP/IP protocol.

## Requirements

- Wireshark installed on your machine.
- A physical wired network to capture packets from.
- Basic understanding of networking concepts, including TCP/IP.

## Getting Started

1. Install [Wireshark](https://www.wireshark.org/).
2. Set up your physical wired network environment for packet capture.
3. Follow the steps outlined in the project to capture and analyze packets.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
