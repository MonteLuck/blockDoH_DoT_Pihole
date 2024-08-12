# Pi-hole DoH/DoT Blocklist

This repository provides a blocklist for Pi-hole that blocks known DNS-over-HTTPS (DoH) and DNS-over-TLS (DoT) servers. This helps ensure that all DNS queries are routed through your Pi-hole, preventing clients from bypassing Pi-hole's filtering by using external encrypted DNS services.

## How to Add the Blocklist to Pi-hole

Follow these steps to add this blocklist to your Pi-hole setup:

### 1. Download the Blocklist

Clone this repository or download the `doh_dot_blocklist.txt` file directly:

```bash
git clone https://github.com/yourusername/pihole-doh-dot-blocklist.git
