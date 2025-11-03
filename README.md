![License: MIT](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-experimental-orange)
![Build](https://img.shields.io/badge/build-WIP-lightgrey)
![Focus](https://img.shields.io/badge/focus-resilience-blue)
![Signals](https://img.shields.io/badge/signals-RF%2C%20GNSS%2C%20ADS--B%2C%20DVB--T%2C%20GSM-green)
![Philosophy](https://img.shields.io/badge/philosophy-physics%20over%20feeds-purple)

# heartbeat-sentinel
A device that doesn't trust the internet to tell me the world is fine.

A Raspberry Pi + SDR system that monitors fundamental real-world signals
to detect whether civilization is operating normally — *without relying on the internet as a single source of truth.*

This project combines radio sensing, network heartbeat checks, independent infrastructure signals, and logic/anomaly analysis to build a **physical-layer uptime monitor for society**.

### Why?

Modern systems fail quietly.
Networks hide outages behind cached UIs.
Cloud services collapse silently.
News can lie — physics can’t.

This project asks one simple question:

> *"Is the world still running — or am I just offline?"*

## Status

`Work in progress — open build`

### Core Signals Monitored

| Category | Indicator |
|---|---|
Internet | Global routing / DNS roots / multi-continent ping |
Power | Local AC sentinel device |
Wireless presence | Nearby Wi-Fi SSIDs vs house power |
Broadcast | FM carriers, DVB-T multiplexes |
Cellular | GSM beacon presence (SDR) + attach checks (modem) |
Air traffic | ADS-B aircraft beacons |
Navigation / Space | GNSS lock & satellite count |
Amateur radio | APRS / ham packet presence |

### What makes this different?

- Multiple independent, physics-based signals
- Avoids “internet tunnel vision”
- Anti-false-positive logic
- Optional local LLM for anomaly explanation
- **Edge-resilient**: works in total internet outage
- *Technological existentialism with engineering discipline*

## Repository Contents

- `/sensors/` — pseudocode for each signal module
- `/docs/` — architecture diagrams & philosophy
- `/data/` — (future) sample logs
- `LICENSE` — open for community
- This README — story + motivation + technical scope

## Contributing

Ideas and data welcome —  
this project is about **citizen resilience engineering**.

### Civil Ethics Notice

This project exists to promote **civil resilience, transparency and peace**.  
Do not use it for fearmongering, coercion, surveillance, or harm.

If you build, build for humanity.

