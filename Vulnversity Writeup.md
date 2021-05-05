## Vulnversity Writeup (THM)

#### Outline

#### [Task 1 - Deploy the machine](#Task1)
#### [Task 2 - Reconnaissance](#Task2)
#### [Task 3 - Locating directories using GoBuster](#Task3)
#### [Task 4 - Compromise the webserver](#Task4)
#### [Task 5 - Privilege Escalation](#Task5)
#### [Additional Notes](#misc)
* * *

### <a id="Task1"></a>Task 1 - Deploy the machine
**No answer required**

* * *
### <a id="Task2"></a>Task 2 - Reconnaissance

**2.1.** **No answer required**

**2.2.** _Scan the box, how many ports are open?_  
Answer: <ins>6</ins>  
\- command used: `nmap -A -p- -sT -vvv <ip>`
	\- Enumerate for as much information as possible. (more often than not, 1 scan is not sufficient to ensure you've got all the infor you need)  
	\- nmap scan in aggressive mode `-A` & all ports `-p-` with TCP Connect Scan `-sT`

**2.3.** _What version of the squid proxy is running on the machine?_  
Answer: <ins>3.5.12</ins>  

**2.4.** _How many ports will nmap scan if the flag -p-400 was used?_  
Answer: <ins>400</ins>  

**2.5.** _Using the nmap flag -n what will it not resolve?_  
Answer: <ins>DNS</ins>
\- tip: [Explain Shell](https://explainshell.com/) is an online resource which can give a quick explaination of the command + flag 

**2.6.** _What is the most likely operating system this machine is running?_  
Answer: <ins>Ubuntu</ins>  
\- tip: initial scan for OS detection `-O`, does not review the OS type. But if you look at the services for port 22, Ubuntu's SSH service is open.

**2.7.** _What port is the web server running on?_  
Answer: <ins>3333</ins>  
\- tip: Doing a quick google search on the services on the machine, which will show what the services are used for and deduction can be made from there

**2.8.**  **No answer required**

* * *
### <a id="Task3"></a>Task 3 - Locating directories using GoBuster

**3.1.**  **No answer required**

**3.2.** _What is the directory that has an upload form page?_  
Answer: <ins>/internal/</ins>  
Steps:
	1) Use gobuster too enumerate for directories.
		command: `gobuster dir -e -t 64 -u <ip> -w /usr/share/wordlists/<any_wordlist>`
		wordlist used: `/usr/share/wordlists/dirbuster/directories.jbrofuzz`
	2) 

* * *
### <a id="Task4"></a>Task 4 - Compromise the webserver

**4.1.** _Try upload a few file types to the server, what common extension seems to be blocked?_  
Answer: <ins></ins>  

**4.2.** **No answer required**

**4.3.** _Run this attack, what extension is allowed?_  
Answer: <ins></ins>  

**4.4.** **No answer required**

**4.5.** _What is the name of the user who manages the webserver?_  
Answer: <ins></ins>  

**4.6.** _What is the user flag?_  
Answer: <ins></ins>  

* * *
### <a id="Task5"></a>Task 5 - Privilege Escalation

**5.1.** _On the system, search for all SUID files. What file stands out?_  
Answer: <ins></ins>  

**5.2.** _Its challenge time! We have guided you through this far, are you able to exploit this system further to escalate your privileges and get the final answer?_  
_Become root and get the last flag (/root/root.txt)_  
Answer: <ins></ins>  

* * *
### <a id="misc"></a>Additional Notes
Summary:  
	1) Enumerate for services/info with Nmap
	2) Enumerate directories on web server with GoBuster
	3) 

