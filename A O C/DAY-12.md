<h3 align="left">DAY12 [Networking-Sharing Without Caring]
</h3>
<br>
<p align="left">1. Scan the target server with the IP <code>MACHINE_IP</code> Remember that MS Windows hosts block pings by default, so we need to add <code>-Pn</code>, for example, <code>nmap -Pn MACHINE_IP</code> for the scan to work correctly. How many TCP ports are open?
<p>
  
```
7
```
<br>
<p align="left">2. In the scan results you received earlier, you should be able to spot NFS or mountd, depending on whether you used the -sV option with Nmap or not. Which port is detected by Nmap as NFS or using the mountd service?.<p>
  
```
2049
```
<br>
<p align="left">3. How many shares did you find?<p>
  
```
4
```
<br>
<p align="left">4. How many shares show “everyone”?<p>
  
```
3
```
<br>
<p align="left">5. What is the title of file 2680-0.txt?<p>
  
```
meditations
```
<br>
<p align="left">6. It seems that Grinch Enterprises has forgotten their SSH keys on our system. One of the shares contains a private key used for SSH authentication (<code>id_rsa</code>). What is the name of the share?.<p>
  
```
confidential
```
<br>
<p align="left">7. We can calculate the MD5 sum of a file using <code>md5sum FILENAME</code>. What is the MD5 sum of <code>id_rsa</code>?<p>
  
```
3e2d315a38f377f304f5598dc2f044de
```
<br>
<br><br>
<a href="https://github.com/n00bcooD3R/advent-of-cyber3">GO-BACK</a>
