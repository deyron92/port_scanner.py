# Project Overview – Python TCP Port Scanner

## Purpose

Identify open TCP ports across a specified port range on any host. Useful for educational, network automation, and security awareness scenarios.

## How It Works

- Uses the `socket` library to probe each port
- Times out after 0.5s if unreachable
- Outputs open ports and scan duration

## Enhancements Possible

- Parallel port scanning (via threads or async)
- UDP port scanning
- Result logging with timestamps
