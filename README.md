# DNS Profile Switcher

A lightweight Windows utility that allows gamers and power users to
quickly switch between popular public DNS providers.

## Features

-   Switch between:
    -   Cloudflare (1.1.1.1)
    -   Google (8.8.8.8)
    -   Quad9 (9.9.9.9)
    -   OpenDNS (208.67.222.222)
    -   Automatic (DHCP)
-   Supports IPv4 and IPv6
-   Flush DNS cache automatically
-   DNS latency testing
-   Detects active physical adapters (Ethernet / Wi-Fi)
-   Windows 10 & Windows 11 compatible
-   Requires Administrator privileges

## Why Use This?

For gamers, changing DNS can improve:

-   Initial server connection speed
-   Domain resolution time
-   Reliability depending on region

This tool makes switching DNS profiles quick and safe.

## Usage

1.  Run `DnsProfileSwitcher.exe`
2.  Approve the Administrator prompt
3.  Select a DNS option from the menu

## DNS Latency Testing

The tool can test multiple DNS providers and display average response
time.\
Lower values generally indicate faster DNS resolution from your
location.

Note: Small differences (under \~5--10ms) usually have negligible impact
on gaming performance.

## Building From Source

Requires: - Visual Studio 2022 - .NET 8.0

Build in Release mode and publish as: - Self-contained - win-x64 -
Single file

## License

MIT License

## Disclaimer

Changing DNS settings may affect network behavior.\
Always revert to Automatic (DHCP) if needed.
