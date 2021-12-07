<h3 align="left">DAY7 [Web Exploitation-Migration Without Security]
</h3>
<br>
<p align="left">1. Interact with the MongoDB server to find the flag. What is the flag?<p>
  
```
THM{884a5e6662a9763f7df23ee59d944f9}
```
<br>
  <p align="left">2. We discussed how to bypass login pages as an admin. Can you log into the application that Grinch Enterprise controls as <code>admin</code> and retrieve the flag?<br>Use the knowledge given in AoC3 day 4 to setup and run Burp Suite proxy to intercept the HTTP request for the login page. Then modify the POST parameter.</p>
<p align="center">
  <img width="800" height="400" alt="Your internet speed sucks" src="11ebe0504325632b2690ebb147fdcf58.png"></img></p>

```
THM{b6b304f5d5834a4d089b570840b467aB}
```
<br>
<p align="left">3. Once you are logged in, use the gift search page to list all usernames that have <code>guest</code> roles. What is the flag?<p>
  
```
THM{2ec099f2d602cc4968c5267970be1326}
```
<br>
  <p align="left">4. Use the gift search page to perform NoSQL injection and retrieve the <code>mcskidy</code> record. What is the details recor?<p>
  
```
ID:6184f516ef6da50433f100f4:mcskidy:admin
```
<br><br>
<a href="https://github.com/n00bcooD3R/advent-of-cyber3">GO-BACK</a>
