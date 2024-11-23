![Alt text]()

# Port_Scanner
A lightweight and efficient port scanner tool built in Python. This tool allows users to scan target hosts for open ports, identify active services, and perform basic network reconnaissance. Designed for learning and real-world network security assessments

## Features
- Fast and customizable port scanning.
- Supports scanning multiple hosts.
- Flexible configuration for port ranges and timeout settings.
- Provides detailed service and banner information.

## Installation

```bash
git clone https://github.com/ashu9335/Port_Scanner.git
cd Port_Scanner
python portscanner.py
```
## Usage

```
python portscanner.py -h
```
This will display help for the tool. Here are all the switches it supports.
```
usage: portscanner.py [-h] [-t THREADS] [-ip HOST] [-s START] [-e END]

options:
  -h, --help            show this help message and exit
  -t THREADS, --threads THREADS
                        Specify Threads(Default 600 (MAX - 849))
  -ip HOST, --Target HOST
                        Specify Target IP address
  -s START, --start_port START
                        Specify Starting Port(Default 1)
  -e END, --end_port END
                        Specify Ending Port (Default 65535)
```

