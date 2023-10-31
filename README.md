# Security

Wi-Fi Deauthentication Tool

Introduction
Wi-Fi Deauthentication Tool is a command-line utility designed for educational purposes, allowing you to perform various actions related to Wi-Fi networks. This tool is intended for legitimate penetration testing, security research purposes, and network devices that you own or have permission to test.

Features
Scan for Wi-Fi networks: Discover nearby Wi-Fi networks and view their details.
Select a Wi-Fi network for further actions: Choose a specific Wi-Fi network for additional actions.
Deauthenticate a client from a Wi-Fi network: Deauthenticate a specific client from a selected Wi-Fi network.
Deauthenticate all clients from a Wi-Fi network: Deauthenticate all clients connected to a selected Wi-Fi network.
Check Wi-Fi Adapter Status: Get the status of the Wi-Fi adapter.
Change Wi-Fi Adapter Interface Name: Modify the interface name of the Wi-Fi adapter.
Prerequisites
Before using this tool, ensure that you have the following prerequisites:

Linux environment
Airodump-ng and Aireplay-ng tools installed
Proper permissions to execute the script
If you don't have airodump-ng and aireplay-ng installed on your system, you can install them using the following steps:

Install aircrack-ng package:

For Debian-based systems, run: sudo apt-get install aircrack-ng
For Red Hat-based systems, run: sudo yum install aircrack-ng
Once the aircrack-ng package is installed, airodump-ng and aireplay-ng should be available in your system.

Usage
Clone the repository or download the script.
Ensure that the script has executable permissions (chmod +x wifideauth.sh).
Run the script using sudo ./wifideauth.sh.
Follow the on-screen menu prompts to choose the desired actions.
Please note that unauthorized attacks on devices that you do not own or do not have permission to test are illegal and unethical. Performing such attacks can lead to severe consequences, including legal actions, criminal charges, and penalties. The author of this tool shall not be held responsible for any damages or liabilities caused by the use or misuse of this tool. Always ensure that you have proper authorization and legal permissions before using this tool. Use it responsibly, respect privacy and security, and comply with all applicable laws and regulations.

IMPORTANT: This tool comes with no guarantees or warranties. The author will not be responsible for any consequences resulting from the use or misuse of this tool. Use it responsibly and at your own risk.
