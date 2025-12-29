# Absolute Security (Computrace) Domain Blocklist

A comprehensive domain blocklist for Absolute Software (formerly Computrace) that can be used with AdGuard Home, AdGuard DNS, Pi-hole, or other DNS filtering solutions.

## About Absolute Software / Computrace

Absolute Software (formerly known as Computrace) is a remote monitoring and management software that is often pre-installed in computer firmware (BIOS/UEFI). While marketed as an anti-theft solution, it has raised privacy concerns due to:

- Persistent nature (difficult to remove, even after OS reinstalls)
- Remote access capabilities
- Data transmission to third-party servers
- Potential security vulnerabilities

This blocklist helps users block communication with Absolute's servers, preventing the software from phoning home.

## What Gets Blocked

This blocklist includes domains for:

- Absolute Software agent communication endpoints
- Computrace legacy infrastructure
- Absolute cloud services and portals
- Update and download servers
- Analytics and telemetry endpoints
- RPC proxy servers

## Contributing

If you discover additional Absolute/Computrace domains that should be blocked, please:

1. Open an issue with the domain(s)
2. Provide evidence/source of the domain being used by Absolute
3. Submit a pull request with the addition

## Disclaimer


This list contains domains suspected to be associated*with
Absolute Software / Computrace based on observed behavior and research.
Entries may be inaccurate or change over time, and blocking them
may have unintended effects on other services.
Review and use at your own discretion.

## License

MIT License - See LICENSE file for details
