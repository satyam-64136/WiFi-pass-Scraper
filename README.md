# Wi-Fi Password Extractor and Emailer

This tool extracts saved Wi-Fi profiles and their passwords from a Windows machine and sends the data to your email. It's stealthy, portable, and self-deleting, with a compact size of just **1.82 KB**.

## Features

- **Wi-Fi Password Extraction:** Retrieves SSIDs and passwords from saved Wi-Fi profiles.
- **Email Reporting:** Sends the extracted data to a predefined email address.
- **Portable Execution:** Comes as an `.exe` file that auto-executes when plugged in via a USB drive.
- **Self-Cleaning:** Deletes itself after execution, leaving no traces.

## How to Use

1. **Portable Attack Mode:**
   - Copy the `.exe` file to a USB drive.
   - Convert the USB drive to an auto-execution USB by modifying its autorun settings.
   - Plug the USB into the target system.
   - Wait 10 seconds for execution and unplug. 
   - The passwords will be emailed to you automatically.

2. **Manual Execution (Optional):**
   - Run the Python script directly or execute the `.exe` on the target machine.

## Notes

- Modify the script to set your email credentials (`from` email, `to` email, and app-specific password).
- Ensure the target machine has internet access for email transmission.

## Disclaimer

This tool is for **educational purposes only**. Unauthorized use of this tool is illegal and unethical. Use responsibly and only with explicit permission.
