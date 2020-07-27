# Xcorp

## Description
```
Author: Artur Khanov (@awengar)

We got into the XCorp network and captured some traffic from an employee's machine. Looks like they were using some in-house software that keeps their secrets.

xcorp.tar.gz
```

## Preview
Unzip has a pcap file.

![screenshot](../.JPG/xcorp_pcap.JPG)

## Checkpoint
In-house software and username.

step1 - Extract files from wireshark.

![screenshot](../.JPG/xcorp_extract1.JPG)

step2 - Execute extracted files.

![screenshot](../.JPG/xcorp_extract2.JPG)

step3 - Find a user in the pcap.

![screenshot](../.JPG/xcorp_finduser.JPG)

step4 - Input username.

![screenshot](../.JPG/xcorp_inputuser.JPG)

## Flag
cybrics{53CuR1tY_N07_0b5CuR17Y}
