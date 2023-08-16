#NOTE
1. pcap is required.
2. sudo previledges in debian based systems (havent tested in windows or mac)
3. To improve code so as not to hard-code the interface to check as a parameter in the pcap.OpenLive method

# in-packet-2
Watches the computers interfaces and logs external IP. The watcher file watches to see if the log file is updated via a html page

# watcher file is still a work in progress
Uses gorilla websockets to watch the log file if it changes.

# privateIP
uses regex to demistify the origin of the packet
