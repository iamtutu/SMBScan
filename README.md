# SMBScan
Scans SMB for Vulnerabilities Assessment

Work in progress, looking to implement several things still
Uses nmap but packages all the NSE scans in one script for quick assessment instead of having to pop each NSE one by one!
Also does Enum4linux with -e flag and nbtscan with -n flag.

Currently uses several dependencies to expedite the Active Information Gathering phase.
These Dependencies are:
*Nmap
*Enum4linux
*nbtscan

It can scan a subrange since it just uses nmap for the heavy lifting.
