# Tuya-Wifi-Plug

Set up Rasperberry Pi as a wifi hotspot https://thepi.io/how-to-use-your-raspberry-pi-as-a-wireless-access-point/
Connect the plug to the hotspot
Run tcpdump: sudo tcpdump -ni br0 -s0 ether host dc:4f:22:c8:6d:d7 -w /home/pi/smartlife.pcap
Turn on/off the switch remotely a few times
