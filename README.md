# retiscraper

# Reticulum TCPInterface Scraper v1.0 by F

# DESCRIPTION:
This is a python script tool to automatically find active TCPInterface servers, list them and select the servers you want to add to Reticulum config automatically without editing the config file manually.

Active TCPInterfaces are fetched from http://reticulumitalia.n-et.org/server-status.php , an experimental php page with underlying python scripts to get a list of working or not servers.

The script will automatically find the path of your reticulum config file on any system to add the desired tcpinterface.

It also make duplicate check on your config file because double tcpinterfaces may cause problems on reticulum launch.

It will fetch the server list from that website and list on screen all available working tpcinterfaces. 

Choose the server(s) you want to add to your config and you are done!

Launch it and follow on screen info.


# REQUIREMENTS: 
- os , to find the .reticulum config folder and file , usually is included in python
- requests , to reach the file list online on the webpage. install with: pip install requests

# INSTALLATION:
Download the python script from this github release and run with:
- python retiscraper.py
(python or python3 based on your system)

# SCREENSHOT:
![retiscraper](https://github.com/user-attachments/assets/6f3a6112-010a-4576-924c-a4daff359659)
