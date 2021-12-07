<h3 align="left">DAY6 [Web Exploitation-Patch Management Is Hard]
</h3>
<br>
<p align="left">1. Deploy the attached VM and look around. What is the entry point for our web application?</p>
  
```
err
```
  <br>
<p align="left">2. Use the entry point to perform <code>LFI</code> to read the <code>/etc/flag</code> file. What is the flag?</p>
  
```
THM{d29e08941cf7fe41df55f1a7da6c4c06}
```
  <br>
  <p align="left">3. Use the PHP filter technique to read the source code of the <code>index.php.</code> What is the <code>$flag</code> variable's value?</p>
  
```
THM{791d43d46018a0d89361dbf60d5d9eb8}
```
  <br>
      <p align="left">McSkidy forgot his login credential. Can you help him to login in order to recover one of the server's passwords<br>4. Now that you read the <code>index.php</code>, there is a login credential PHP file's path. Use the PHP filter technique to read its content. What are the username and password?</p>
  
```
McSkidy:A0C315Aw3s0m
```
  <br>
          <p align="left">5. Use the credentials to login into the web application. Help McSkidy to recover the server's password. What is the password of the <code>flag.thm.aoc</code> server? </p>
  
```
THM{552f313b52e3c3dbf5257d8c6db7f6f1}
```
  <br>
              <p align="left">6. The web application logs all users' requests, and only authorized users can read the log file. Use the LFI to gain RCE via the log file page. What is the hostname of the webserver? The log file location is at <code>./includes/logs/app_access.log</code>.</p>
  
```
lfi-awesome-59aedca683fff9261263bb084880c965
```
  <br>
                  <p align="left">Bonus: The current PHP configuration stores the PHP session files in <code>/tmp.</code> Use the LFI to call the PHP session file to get your PHP code executed.<p>
  
```
No answer needed.
```
  <br>
<br><br>
<a href="https://github.com/n00bcooD3R/advent-of-cyber3">GO-BACK</a>
