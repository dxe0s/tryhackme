## CC: Pen Testing Writeup (THM)

#### Outline

#### [Task 1 - Introduction](#Task1)
#### [Task 2 - Section 1 (Network Utilities - Nmap)](#Task2)
#### [Task 3 - Section 1 (Network Utilities - Netcat)](#Task3)
#### [Task 4 - ](#Task4)
#### [Task 5 - ](#Task5)
#### [Task 6 - ](#Task6)
#### [Task 6 - ](#Task6)
#### [Task 7 - ](#Task7)
#### [Task 8 - ](#Task8)
#### [Task 9 - ](#Task9)
#### [Task 10 - ](#Task10)
#### [Task 11 - ](#Task11)
#### [Task 12 - ](#Task12)
#### [Task 13 - ](#Task13)
#### [Task 14 - ](#Task14)
#### [Task 15 - ](#Task15)
#### [Task 16 - ](#Task16)
#### [Task 2 - ](#Task17)
#### [Task 3 - ](#Task18)
#### [Task 4 - ](#Task19)
#### [Task 5 - ](#Task20)
#### [Task 6 - ](#Task21)
#### [Task 6 - ](#Task22)
#### [Task 7 - ](#Task23)
#### [Task 8 - ](#Task24)
#### [Additional Notes](#misc)
* * *

### <a id="Task1"></a>Task 1 - Introduction
**No answer required**

* * *
### <a id="Task2"></a>Task 2 - Section 1 (Network Utilities - NMap)

\-note: export ip to an env variable before scanning, to save time from having to type the ip always 
`export ip=<insert ip>`

**2.1.** _What does nmap stand for?_  
Answer: <ins>Network Mapper</ins>  

**2.2.** _How do you specify which port(s) to scan?_  
Answer: <ins>-p</ins>  
![ccPT_2 2](https://user-images.githubusercontent.com/68154769/117125241-d9dc6c80-adcb-11eb-8d36-8d9092801f53.png)

**2.3.** _How do you do a "ping scan"(just tests if the host(s) is up)?_  
Answer: <ins>-sn</ins>  
![Uploading ccPT_2.3.png…]()
\-tip: scanning all ports with <-p-> takes a very long time for just needing to know the host is up

**2.4.** _What is the flag for a UDP scan?_  
Answer: <ins>-sU</ins>  
![ccPT_2 4](https://user-images.githubusercontent.com/68154769/117125330-fbd5ef00-adcb-11eb-9b09-3c67006c31d9.png)

**2.5.** _How do you run default scripts?_  
Answer: <ins>-sC</ins>  
![ccPT_2 5](https://user-images.githubusercontent.com/68154769/117125343-00020c80-adcc-11eb-8198-3a57c51d0b71.png)

**2.6.** _How do you enable "aggressive mode"(Enables OS detection, version detection, script scanning, and traceroute)_  
Answer: <ins>-A</ins>  

**2.7.** _What flag enables OS detection?_  
Answer: <ins>-O</ins>  

**2.8.** _How do you get the versions of services running on the target machine _  
Answer: <ins>-sV</ins>  

**2.9.** 
<ins>Click Completed</ins>  

**2.10.** _How many ports are open on the machine? _  
Answer: <ins>1</ins>  
![ccPT_2 10](https://user-images.githubusercontent.com/68154769/117125428-190abd80-adcc-11eb-8afc-14129882fa72.png)

**2.11.** _What service is running on the machine?_  
Answer: <ins>Apache</ins>  

**2.12.** _What is the version of the service?_  
Answer: <ins>2.4.18</ins>  

**2.13.** _What is the output of the http-title script(included in default scripts)_  
Answer: <ins>
Apache2 Ubuntu Default Page: It Works</ins>  
command : `nmap -p 80 --script http-title <ip>`
\- this command is executing the script 'http-title' on port 80 which we initially scanned for in Task 2.10
\-tip: for better understanding, do [NMap](https://tryhackme.com/room/furthernmap) room first
\-note: use man page for Nmap to check the flags used. 1 quick way to get the command you want, is to use grep. e.g. `man nmap | grep OS`

* * *
### <a id="Task3"></a>Task 3 - 

**3.1.** _insert qn_  
Answer: <ins>insert ans</ins>  

* * *
### <a id="Task4"></a>Task 4 - 

**4.1.** _insert qn_  
Answer: <ins>insert ans</ins>  

* * *
### <a id="Task5"></a>Task 5 - 

**5.1.** _insert qn_  
Answer: <ins>insert ans</ins>  

* * *
### <a id="Task6"></a>Task 6 - 



* * *
### <a id="Task7"></a>Task 7 - 



* * *
### <a id="Task8"></a>Task 8 - 



* * *
### <a id="misc"></a>Additional Notes


