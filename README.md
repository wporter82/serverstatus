#Server Status Script

##Purpose
Github, twitter, amazon, reddit and many other sites were taken down due to a 
DDoS attack on DynDNS. I created this script to ping a list of servers to let me
know when they come back up.

##Usage
This was designed to be used with the watch command like so:

	watch -tcn 120 serverstatus

The t option means "don't display the watch title line"
The c option tells watch to display colors
The n option is how often to run the script in seconds

