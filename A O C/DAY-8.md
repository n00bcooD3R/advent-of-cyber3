<h3 align="left">DAY8 [special by John Hammond Santa's Bag of Toys]
</h3>
<br>
<b><p align="left">Read the premise above, start the attached Windows analysis machine, and find the transcription logs in the <code>SantasLaptopLogs</code> folder on the Desktop.<p></b>
<p>If you want to login to the machine manually via RDP, the credentials are Administrator as the username, and grinch123! as the password.</p>
  
```
No answer needed.
```
<br>
<p>Each transcription log is a simple plain text file that you can open in any editor of your choice. While the filenames are random, you can get an idea as to which log "comes first" by looking at the Date Modified or Date Created attributes, or the timestamps just before the file extension!</p>
<p>Open the first transcription log. You can see the commands and output for everything that ran within PowerShell, like <code>whoami</code> and <code>systeminfo!</code> </p>
<br>
<p align="left">1. What operating system is Santa's laptop running ("OS Name")?</p>
  
```
microsoft windows 11 pro
```
<br>
<p><b>Review each transcription log to get an idea for what activity was performed on the laptop just after it went missing. In the "second" transcription log, it seems as if the perpetrator created a backdoor user account!</b></p>
<br>
<p align="left">2. What was the password set for the new "backdoor" account?</p>
  
```
grinchstolechristmas
```
<br>
<p align="left">3.In one of the transcription logs,  the bad actor interacts with the target under the new backdoor user account, and copies a unique file to the Desktop. Before it is copied to the Desktop, <b>what is the full path of the original file?</b></p>
  
```
C:\Users\santa\AppData\Local\Microsoft\Windows\UsrClass.dat
```
<br>
<p align="left">4.The actor uses a <a href="https://lolbas-project.github.io/lolbas/Binaries/Certutil/">Living Off The Land</a> binary (LOLbin) to encode this file, and then verifies it succeeded by viewing the output file. <b>What is the name of this LOLbin?</b></p>
  
```
certutil.exe
```

<h2>there a reading to be done . yu can read it on challange page <a href="https://tryhackme.com/room/adventofcyber3">here</a></h2>
<br>
<p align="left">5. Drill down into the folders and see if you can find anything that might indicate how we could better track down what this SantaRat really is. <b>What specific folder name clues us in that this might be publicly accessible software hosted on a code-sharing platform?<b></p>
  
```
.github
```
<br>
<p align="left">6. Additionally, there is a unique folder named "Bag of Toys" on the Desktop! This must be where Santa prepares his collection of toys, and this is certainly sensitive data that the actor could have compromised. <b>What is the name of the file found in this folder?</b></p>
  
```
bag_of_toys.zip
```
<br>
<p align="left">7. <b>What is the name of the user that owns the SantaRat repository?</b></p>
  
```
Grinchiest
```
<br>
<p align="left">8. Explore the other repositories that this user owns. <b>What is the name of the user that owns the SantaRat repository?</b></p>
  
```
operation-bag-of-toys
```
<br>
<p align="left">9. Read the information presented in this repository. It seems as if the actor has, in fact, compromised and tampered with Santa's bag of toys! You can review the activity in the transcription logs. It looks as if the actor installed a special utility to collect and eventually exfiltrate the bag of toys. <b>What is the name of the executable that installed a unique utility the actor used to collect the bag of toys?</b>
</p>
  
```
uharc-cmd-install.exe
```
<br>
<p align="left">10. Following this, the actor looks to have removed everything from the bag of toys, and added in new things like coal, mold, worms, and more! <b>What are the contents of these "malicious" files (coal, mold, and all the others)?</b><p>
  
```
GRINCHMAS
```
<br>
  <p align="left">11. <b>What is the password to the original bag_of_toys.uha archive?</b>(You do not need to perform any password-cracking or bruteforce attempts)<p>
  
```
TheGrinchiestGrinchmasOfAll
```
<br>
  <p align="left">12. <b>How many original files were present in Santa's Bag of Toys?</b><p>
  
```
228
```
<br><br>
<a href="https://github.com/n00bcooD3R/advent-of-cyber3">GO-BACK</a>



  
