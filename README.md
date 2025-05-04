# portPicker
Automated port extractor for greppable Nmap outputs

It has to be located in the PATH for example: /usr/local/bin 

This script is designed so that when you run Nmap, you extract the information using the -oG option. After that, you pass the script to the file so it extracts the ports, then performs version detection and a basic script scan to save time. If we get 20 ports, we won't have to enter them manually, as they will be automatically copied to the clipboard, avoiding the need to scan all 65,535 ports.
