# Network-Scanner-Tool
Network Scanner is a lightweight ARP-based LAN discovery tool written in Python. It enumerates live hosts on a local IPv4 network by sending ARP requests, collects IP and MAC addresses, and optionally attempts reverse DNS lookups for hostnames. Designed for learning, lab use, and authorized security assessments.
Key features
Fast local network discovery using ARP (Layer 2).
Returns IP, MAC and hostname (when resolvable).
Simple, dependency-light Python implementation.
Multi-threaded scanning for improved speed.
Safe and readable tabular output suitable for reports.
Easily extensible (thread pool, CSV/JSON export, MAC OUI lookup).

Expected output
IP                    MAC                  Hostname
--------------------------------------------------------------------------------
192.168.1.1           00:11:22:33:44:55    router.local
192.168.1.10          aa:bb:cc:dd:ee:ff    Unknown
