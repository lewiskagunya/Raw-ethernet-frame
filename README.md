🕸️ Layer 2 Analysis: Raw Ethernet Frame Research
Project: Ethernet Frame Capture & Header Parsing
📌 Project Overview

This project focuses on the lowest level of network communication: the Ethernet Frame. Developed in C, this tool interacts with the Network Interface Card (NIC) in Promiscuous Mode to capture, dissect, and analyze raw Layer 2 frames, bypassing the standard TCP/IP stack processing.
🛠️ Technical Depth

By utilizing AF_PACKET sockets in Linux, this project demonstrates mastery over:

    Frame Structure: Manual parsing of the Preamble, Destination MAC, Source MAC, and EtherType.

    Promiscuous Mode: Programming the interface to intercept all traffic on the local segment, not just traffic intended for the host.

    Hexadecimal Decoding: Converting raw buffer streams into human-readable hardware addresses.

    Endianness Handling: Managing Big-endian (Network Byte Order) vs. Little-endian (Host Byte Order) during data interpretation.
