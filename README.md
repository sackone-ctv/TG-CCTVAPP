# CamHack Tool For Education

A powerful camera scanning and access tool for security testing purposes.

## Requirements

- Termux (Android)
- Python 3.x
- Internet connection

## Installation in Termux

1. First, set up storage access:
```bash
termux-setup-storage
```

2. Install Python and required packages:
```bash
pkg install python
pkg install python-pip
pkg install git
```

3. Update and upgrade packages:
```bash
pkg update && pkg upgrade
```

4. Install Python dependencies:
```bash
pip install colorama
pip install aiohttp
pip install art
pip install pycryptodome
pip install requests
```

5. Navigate to downloads directory:
```bash
cd storage/downloads
```

4. Clone this repository:
```bash
git clone https://github.com/sackone-ctv/TG-CCTVAPP
cd TG-CCTVAPP
```

## Usage

1. Run the main script:
```bash
python camhack.py
```

2. Choose from the following options:
   - Script 1: IP range scanner
   - Script 2: Camera configuration decryptor
   - Script 3: Camera access tool

## Required Files

Before running the scripts, make sure you have these files in the same directory:
- `host.txt`: Contains target IP addresses
- `user.txt`: Contains usernames to try
- `pass.txt`: Contains passwords to try

## Features

### Script 1: IP Scanner
- Scans a range of IP addresses
- Identifies potential camera endpoints
- Saves found IPs to host.txt

### Script 2: Configuration Decryptor
- Decrypts camera configurations
- Extracts credentials
- Saves snapshots to VDB directory

### Script 3: Camera Access
- Tests camera access with provided credentials
- Saves successful connections
- Downloads camera snapshots

## Important Notes

- This tool is for educational purposes only
- Use only on systems you have permission to test
- Respect privacy and legal boundaries
- The tool may not work on all camera models
- Some features require root access

## Troubleshooting

If you encounter any issues:

1. Check your internet connection
2. Verify all required files exist
3. Ensure you have proper permissions
4. Check if the target IPs are accessible
5. Verify Python dependencies are installed correctly

## Disclaimer

This tool is provided for educational and security testing purposes only. The developers are not responsible for any misuse or illegal activities performed with this tool. Always obtain proper authorization before testing any system.

## Support

For support or questions, please contact:
- Telegram: @SlickMercy 
