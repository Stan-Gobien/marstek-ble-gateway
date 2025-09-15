# Marstek ESPHome BLE Gateway

> ⚠️ **EXPERIMENTAL** - Use at your own risk

ESPHome BLE gateway for Marstek Venus E energy storage systems. Integrates with Home Assistant without cloud connectivity.

## Quick Start

1. Edit `secrets.yaml` with your WiFi credentials
2. Flash to ESP32: `esphome run marstek-ble-gateway.yaml`
3. Add to Home Assistant via ESPHome integration

Auto-detects Marstek devices (starting with "MST"). Only set MAC address manually if you have multiple Marstek devices.

## Features

- Real-time power/battery monitoring
- Device control (power limits, EPS mode)
- Home Assistant Energy Dashboard support
- Local operation only

## Hardware

- ESP32 board
- Marstek Venus E with BLE

## Attribution

Based on excellent work from:
- [esphome-b2500](https://github.com/tomquist/esphome-b2500) by @tomquist
- [hm2500pub](https://github.com/noone2k/hm2500pub) by @noone2k  
- [marstek-venus-monitor](https://github.com/rweijnen/marstek-venus-monitor) by @rweijnen

## Disclaimer

Experimental software. Not affiliated with Marstek Energy. Use at your own risk.