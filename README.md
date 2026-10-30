# USB Device Fingerprinting and Identification

**A Python-based USB device identification and fingerprinting tool for cybersecurity analysis.**

## Project Overview

This project aims to develop a tool that identifies connected USB devices by extracting hardware information and USB descriptors.

The objective is to understand USB device characteristics and explore how device fingerprinting can contribute to cybersecurity and hardware identification.

**Project Status:** In Development

## Objectives

- Detect connected USB devices.
- Extract USB hardware identifiers.
- Analyse USB device descriptors.
- Generate unique device fingerprints using available attributes.
- Explore potential security applications of USB device identification.

## Technologies Used

- Python
- Windows PowerShell
- PyUSB (planned/optional)
- Git and GitHub

## Features

*Features will be updated as development progresses.*

- [ ] USB device detection
- [ ] Vendor ID (VID) extraction
- [ ] Product ID (PID) extraction
- [ ] USB version identification
- [ ] Manufacturer and product information
- [ ] Serial number extraction (when available)
- [ ] USB descriptor analysis
- [ ] Device fingerprint generation
- [ ] Device identification and comparison

## Information Extracted

The tool aims to analyse:

| Attribute | Description |
|---|---|
| VID | Vendor ID |
| PID | Product ID |
| USB Version | USB specification version |
| Device Class | USB device class |
| Manufacturer | Device manufacturer |
| Product | Device product name |
| Serial Number | Device serial number, if available |
| Interfaces | Number of USB interfaces |
| Endpoints | USB endpoint information |

## Project Structure

```text
usb-device-fingerprinting/
├── src/
├── screenshots/
├── docs/
├── README.md
├── requirements.txt
└── .gitignore
```

## Installation

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/usb-device-fingerprinting.git
```

Navigate into the project:

```bash
cd usb-device-fingerprinting
```

Install dependencies when requirements.txt is ready:

```bash
pip install -r requirements.txt
```

## Usage

Instructions and screenshots will be added after implementation.

## Future Improvements

- Detect potentially suspicious USB devices.
- Compare device fingerprints.
- Maintain a database of previously connected devices.
- Generate security alerts for unfamiliar devices.
- Explore USB device anomaly detection.

## Disclaimer

This project is intended for educational and authorized cybersecurity research purposes.

## Author

THARUN PRANAV I G
