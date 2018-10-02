# Tuya-Wifi-Plug
Project Goal:
To understand what send to the plug to turn it on/off
To control the plug by a custom app (web, node, etc.)


Set up Rasperberry Pi as a wifi hotspot https://thepi.io/how-to-use-your-raspberry-pi-as-a-wireless-access-point/
Connect the plug to the hotspot via SmartLife mobile app
Run tcpdump: sudo tcpdump -ni br0 -s0 ether host dc:4f:22:c8:6d:d7 -w /home/pi/smartlife.pcap
Turn on/off the switch remotely, using the Smart Life mobile app a few times
