<h3 align="left">DAY10 [Networking-Offensive Is The Best Defence]
</h3>
<br>
<p align="left">1. Help McSkidy and run <code>nmap -sT MACHINE_IP</code> How many ports are open between 1 and 100?</p>
  
```
2
```
<br>
<p align="left">2. What is the smallest port number that is open?</p>
  
```
22
```
<br>
<p align="left">3. What is the service related to the highest port number you found in the first question?</p>
  
```
http
```
<br>
<p align="left">4. Now run <code>nmap -sS MACHINE_IP</code> Did you get the same results? (Y/N)</p>
  
```
Y
```
<br>
<p align="left">5. If you want Nmap to detect the version info of the services installed, you can use <code>nmap -sV MACHINE_IP</code> What is the version number of the web server?</p>
  
```
Apache httpd 2.4.49
```
<br>
<p align="left">6. By checking the <a href="https://httpd.apache.org/security/vulnerabilities_24.html">vulnerabilities related to the installed web server</a> you learn that there is a critical vulnerability that allows path traversal and remote code execution. Now you can tell McSkidy that Grinch Enterprises used this vulnerability. What is the CVE number of the vulnerability that was solved in version 2.4.51?</p>
  
```
CVE-2021-42013
```
<br>
<p align="left">7. You are putting the pieces together and have a good idea of how your web server was exploited. McSkidy is suspicious that the attacker might have installed a backdoor. She asks you to check if there is some service listening on an uncommon port, i.e. outside the 1000 common ports that Nmap scans by default. She explains that adding <code>-p1-65535</code> or <code>-p-</code> will scan all 65,535 TCP ports instead of only scanning the 1000 most common ports. What is the port number that appeared in the results now?</p>
  
```
20212
```
<br>
<p align="left">8. What is the name of the program listening on the newly discovered port?</p>
  
```
telnetd
```
<br>
<p align="left">9. If you would like to learn more about the topics covered in today’s tasks, we recommend checking out the <a href="https://tryhackme.com/module/network-security">Network Security</a> module.</p>
  
```
No Answer needed.
```
<br><br>
<a href="https://github.com/n00bcooD3R/advent-of-cyber3">GO-BACK</a>
