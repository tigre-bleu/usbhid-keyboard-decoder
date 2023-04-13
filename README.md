Simple python script to print keyboard entry from captured file.

# How to use

First extract from the pcap file with

```
tshark -r file.pcap -T fields -e usb.capdata > hexoutput.txt
```

Then run the python script

*Inspired from https://bitvijays.github.io/LFC-Forensics.html*
