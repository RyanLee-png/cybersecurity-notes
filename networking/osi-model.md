# OSI Model

## What is the OSI Model?
The OSI (Open Systems Interconnection) model is a conceptual framework that explains how data travels from one device to another over a network.  
It divides network communication into 7 layers, each with a specific role.

## 7 Layers of the OSI Model
1. Physical – cables, signals, hardware
2. Data Link – MAC addresses, switches
3. Network – IP addressing, routing
4. Transport – TCP/UDP, ports
5. Session – session control
6. Presentation – encryption, data formatting
7. Application – HTTP, FTP, DNS

## Why it matters in cybersecurity
Understanding the OSI model helps identify where attacks occur:
- Network layer: IP spoofing
- Transport layer: SYN flood attacks
- Application layer: SQL injection, XSS
- 
## Personal Reflection

Before studying the OSI model, I saw networking as a collection of isolated concepts and memorized protocols without understanding their relationships.

Learning the OSI model changed my mindset. I began to analyze security problems layer by layer instead of blaming the entire system. For example, I now understand why attacks like IP spoofing occur at the network layer, while SQL injection belongs to the application layer.

This structured way of thinking helped me develop a defender’s perspective and is one of the first moments where I started thinking like a cybersecurity student rather than just a learner.

## Current limitations
