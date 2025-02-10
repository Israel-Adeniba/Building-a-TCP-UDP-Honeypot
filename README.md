# Building a TCP/UDP Honeypot

## Objective
This project is a simple yet effective Honeypot designed to detect and log unauthorized access attempts on TCP and UDP ports. By simulating vulnerable services, this tool helps security analysts study attack patterns, identify malicious IPs, and improve network defenses

<h2>Resources and Utilities Used</h2>

- <b>VULTR</b> 
- <b>T-POT</b>
- <b>Elastic</b>


<h2>Program walk-through:</h2>
1. Setup VULTR
2. Set-up and install programs
3. Connecting the Virtual Network; Network environment setup, connecting all devices and the particular network connection established.

   
<h2>Phase 1: Setup VULTR </h2>

  1. </b> Create a VULTR account </b>    [[vultr.com](https://www.vultr.com/?ref=9720742)]
  2. Click on "Deploy" and "Deploy New Server".
<img src="https://imgur.com/eSqU5UB.png" height="80%" width="80%" alt="Building a Cybersecurity Lab Steps"/>
<br />
<br />
  3.  </b> Configure the hardware: </b>
  
  -  We selected "Shared CPU"
  -  We selected the [vc2-6c-16gb 6vCPUs 16GBmemory 320GB SSDstorage]
  -  For the location, choose the location closet to you. The reason for choosing the data center closest to you, is to reduce the latency times, the closer you are to a data center, the lower the latency.
<img src="https://imgur.com/Z6FNGo0.png" height="80%" width="80%" alt="Building a Cybersecurity Lab Steps"/>
<br />
<br />
   4.  </b> Configure software and deploy instance: </b>
  
  -  We selected "Debian" the latet vrsion 12 x64
  -  We entered our Server Hostname and Label
  -  For the Firewall Group we would configure once the VPs
<img src="https://imgur.com/V6d89HL.png" height="80%" width="80%" alt="Building a Cybersecurity Lab Steps"/>
<br />
<br />
