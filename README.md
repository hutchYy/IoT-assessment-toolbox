# IoT-assessment-toolbox (Draft)
All scripts, utilities needed for your IoT assessments

## Utilities

| Utility | Description | Link |
| - | - | - |
| Arduino | IDE to write code and upload it to the differents IoT compatible boards.| |
| Picocom | Minimal dumb-terminal emulator. | |
| BDAddr | Script used to harden bluetooth devices. | Not found need to build it yourself |
| BetterCap | Tool for network related attacks including WiFi, BLE, etc. |  |
| Binwalk | Tool for searching a given binary image for embedded files and executable code. | |
| Create_AP | Tool that is used to generate access points. | https://github.com/oblique/create_ap |
| Cutter | Cutter is a free and open-source reverse engineering platform powered by rizin. | |
| DspectrumGUI | The goal of this app is to make it trivial to demodulate common RF signals, and provide a digital worksheet for your reverse engineering efforts. | https://github.com/tresacton/dspectrumgui |
| Dump1090 | Dump 1090 is a Mode S decoder specifically designed for RTLSDR devices. |  https://github.com/antirez/dump1090 |
| Firmadyne | FIRMADYNE is an automated and scalable system for performing emulation and dynamic analysis of Linux-based embedded firmware | |
| Firmware Analysis Toolkit | / | https://github.com/firmadyne/firmadyne |
| Firmware Analysis Toolkit (FAT) | / | |
| Firmware-Mod-Kit (FMK) | / | |
| GHIDRA | A software reverse engineering (SRE) suite of tools developed by NSA's Research Directorate in support of the Cybersecurity mission. | https://ghidra-sre.org/ |
| GNURadio | GNU Radio is a free & open-source software development toolkit that provides signal processing blocks to implement software radios. | |
| GQRX | Gqrx is an open source software defined radio receiver (SDR) powered by the GNU Radio and the Qt graphical toolkit. | |
| GR-GSM | The aim is to provide set of tools for receiving information transmitted by GSM equipment/devices. | |
| GR-Paint | The goal of this project is to build a software-defined OFDM transmitter that "paints" monochrome images into the waterfall of a receiver. | https://github.com/drmpeg/gr-paint |
| HackRF Tools | Software defined radio peripheral - utilities. | |
| Inspectrum | Inspectrum is a tool for analysing captured signals, primarily from software-defined radio receivers. |  |
| JADx | Dex to Java decompiler. | |
| Kalibrate-RTL | Calculate local oscillator frequency offset using GSM base stations. | |
| KillerBee | KillerBee is a Framework and Tools for Testing & Auditing ZigBee and IEEE 802.15.4 Networks. | https://github.com/riverloopsec/killerbee |
| LibMPSSE | Open source library for SPI/I2C control via FTDI chips. | https://github.com/devttys0/libmpsse |
| Liquid-DSP | Free and open-source signal processing library for software-defined radios written in C. | https://liquidsdr.org/doc/installation/ |
| LTE-Cell-Scanner | An enhanced LTE Cell Scanner/tracker. | https://github.com/JiaoXianjun/LTE-Cell-Scanner |
| NMAP | Nmap is a free and open-source network scanner. | |
| OOK-Decoder | Ook-decoder reads On-Off Keying radio data commonly used in the 433MHz ISM bands using a software defined radio (SDR). | https://github.com/jimstudt/ook-decoder |
| Qiling | Qiling is an advanced binary emulation framework. | https://github.com/qilingframework/qiling |
| radare2 | Free and advanced command line hexadecimal editor. | |
| RFCat | Swiss army knife of sub-GHz radio | |
| RouterSploit | Exploitation Framework for Embedded Devices. | |
| RTL-433 | rtl_433 is a generic data receiver, mainly for the 433.92 MHz, 868 MHz (SRD), 315 MHz, 345 MHz, and 915 MHz ISM bands. | https://github.com/merbanan/rtl_433 |
| Scapy | Packet generator/sniffer and network scanner/discovery (Python 3) | |
| Spectrum Painter | A tool to converts images to IQ streams that look like this when viewed in a waterfall plot. | https://github.com/polygon/spectrum_painter |
| Ubertooth tools- | Ubertooth is an open source wireless development platform suitable for Bluetooth experimentation. | |
| URH (Universal Radio Hacker) | The Universal Radio Hacker (URH) is a complete suite for wireless protocol investigation with native support for many common Software Defined Radios. | https://github.com/jopohl/urh#Installation |

## Installation
Most of the tools can be installed using the **apt** packet manager.
[STILL IN DRAFT]

### Apt

```Bash
sudo apt install arduino picocom bettercap binwalk rizin-cutter dump1090-mutability gnuradio gqrx-sdr gr-gsm hackrf inspectrum jadx kalibrate-rtl nmap radare2 rfcat routersploit python3-scapy ubertooth
```
