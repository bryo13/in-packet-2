# in-packet-2
Watches the computers interfaces and logs external IP. The watcher file watches to see if the log file is updated via a html page

# watcher file is still a work in progress
Uses gorilla websockets to watch the log file if it changes.

# logs package
Writes a log file to the /home directory. (To add file encryption and maybe cloud hosting)

# privateIP
uses regex to demistify the origin of the packet
