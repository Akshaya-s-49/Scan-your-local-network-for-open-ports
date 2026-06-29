Task -1 Scan-your-local-network-for-open-ports

Objective:

Learn to discover open ports on devices within a local network in order to understand network exposure and identify potential security risks.

Tools Used:

nmap ,kali linux

Methodology:

1. Identify the local network range
2. Run a TCP SYN scan with service and OS detection
3. Review the results
4. Generate an HTML report

Scan Results:

Command used:

sudo nmap -sT -sV 10.167.19.xxx -oA task1_results

Summary: 256 IP addresses scanned, 1 host up, scan completed in ~100 seconds.

1.IP Address :10.167.19.XXX 

2.Port :53/tcp 

3.State :open

4.Service:domain (DNS)

5.Version :dnsmasq 2.51
