# Wireshark-for-Beginners-TCP-IP-Protocol-Fundamentals
### Wireshark Overview
Wireshark is a powerful open-source network protocol analyzer that helps users capture and analyze data traffic traveling through a network in real time. It provides a detailed view of data packets, which plays a vital role in users’ network communication analysis, troubleshooting, and ensuring security. Wireshark is an essential tool for network administrators, security experts, developers, and anyone interested in understanding how network protocols work.

Wireshark is commonly used for network troubleshooting. It helps users identify and resolve slow network performance, misconfigurations, or connectivity issues. It is also essential for protocol analysis, especially for breaking down and analyzing complex network protocols. Wireshark is also used in security auditing, where it helps identify vulnerabilities such as insecure communications, misused ports, or protocol abuse. It provides a deep understanding of TCP/IP, HTTP, DNS, and other important network protocols. Security experts use Wireshark for network forensics, where they review network traffic logs to identify malicious activity or data breaches.

### SSL/TLS in Wireshark
SSL (Secure Sockets Layer) and TLS (Transport Layer Security) are cryptographic protocols used for secure communication, which encrypt data in transit and ensure confidentiality and integrity. In Wireshark, SSL/TLS traffic is usually encrypted, so to see its true content, the correct decryption keys are required. However, Wireshark can help with detailed analysis of the SSL/TLS handshake and the cipher suites used. Security analysts use this tool when identifying SSL/TLS-related issues or ensuring secure communication processes.

To fully decrypt Wireshark SSL/TLS traffic, a decryption key, such as a private key or pre-master secret, is required. This is important for security and privacy, as it allows for deep analysis of encrypted communication. Without the decryption key, Wireshark will only display the details of the handshake and the encryption method used, but the content of the communication will remain unreadable.

### Wireshark on Linux Distributions
Although Wireshark is a cross-platform tool, it is particularly popular among Linux distributions. This is because Linux systems offer strong networking support and detailed packet capture capabilities, which enhance Wireshark's functionality. There are also additional security features for running Wireshark on Linux, which are important for penetration testing and secure data analysis.

Since both Wireshark and Linux are open-source, it makes it an attractive choice for users who prefer free software. Some distributions, such as Kali Linux, are specifically designed for penetration testing, making it ideal for running Wireshark. Additionally, by integrating with various Linux networking tools, such as tcpdump or iptables, users can analyze network traffic in more depth. As a result, Wireshark on the Linux platform becomes more powerful and flexible when combined with each other, making it suitable for network analysis or security-related tasks.

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

## Step-by-Step Instructions

### Step 1: Install Wireshark

If you haven't installed Wireshark already, download and install it from the official website:

- [Wireshark Download](https://www.wireshark.org/)

### Step 2: Start Capturing Network Traffic

1. **Open Wireshark**.
2. **Select the network interface**: Choose the interface that corresponds to your physical wired network (e.g., Ethernet, `eth0`, `enp0s3`).
3. **Start capturing**: Click the blue shark fin icon to start capturing packets.
4. **Stop capturing**: Click the red square icon after you've captured enough packets. You can save the capture file (`.pcap` format) for further analysis.

### Step 3: Observing the Internet Layer of the TCP/IP Model

The **Internet Layer** includes protocols like **IP** (e.g., IPv4, IPv6).

- **Filter for IP traffic**: Use the filter `ip` for IPv4 or `ipv6` for IPv6.
  
  Example filter for IPv4:
  ```plaintext
  iP


## Getting Started

1. Install [Wireshark](https://www.wireshark.org/).
2. Set up your physical wired network environment for packet capture.
3. Follow the steps outlined in the project to capture and analyze packets.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
