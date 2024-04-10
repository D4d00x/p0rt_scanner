# Port Scanner

Port Scanner is a Python script for scanning specified ports on a target host to check for open TCP ports.

## Usage

1. Clone the repository:

git clone https://github.com/D4d00x/port-scanner.git


2. Navigate to the project directory:

cd port-scanner


3. Run the script:

python port_scan.py TARGET_HOST -p TARGET_PORTS


Replace `TARGET_HOST` with the IP address or domain name of the target host, and `TARGET_PORTS` with the ports you want to scan, separated by commas (e.g., 21,80).

Example:

python port_scan.py scanme.nmap.org -p 21,80


4. The script will perform a port scan on the specified target host and ports, displaying the results indicating whether each port is open or closed.

## Disclaimer

This script is intended for educational purposes and should only be used on networks where you have explicit permission to perform port scanning. Unauthorized scanning of network ports is illegal and unethical.

## Requirements

- Python 3.x

## Author

Dado Hatipovic @ EC Utbildning/Security Developer
