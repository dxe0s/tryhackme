## Google Dorking Writeup (THM)

#### Outline

#### [Task 1 - Ye Ol' Search Engine](#Task1)
#### [Task 2 - Let's Learn About Crawlers](#Task2)
#### [Task 3 - Enter: Search Engine Optimisation](#Task3)
#### [Task 4 - Beepboop - Robots.txt](#Task4)
#### [Task 5 - SiteMaps](#Task5)
#### [Task 6 - What is Google Dorking?](#Task6)
#### [Additional Notes](#misc)
* * *

### <a id="Task1"></a>Task 1 - Ye Ol' Search Engine
**No answer required**

* * *
### <a id="Task2"></a>Task 2 - Let's Learn About Crawlers

**2.1.** _Name the key term of what a "Crawler" is used to do_  
Answer: <ins>Index</ins>  
![SS_2 1](https://user-images.githubusercontent.com/68154769/116773881-21d95780-aa8b-11eb-83bf-42534ae5346c.png)

**2.2.** _What is the name of the technique that "Search Engines" use to retrieve this information_ about websites?  
Answer: <ins>Crawling</ins>  
![GD_SS_2 2](https://user-images.githubusercontent.com/68154769/116774129-f7889980-aa8c-11eb-8f53-45d1120653a8.png)

**2.3.** _What is an example of the type of contents that could be gathered from a website?_  
Answer: <ins>Keywords<ins>  
![GD_SS_2 3](https://user-images.githubusercontent.com/68154769/116774027-15a1ca00-aa8c-11eb-861e-f57c1ca838b1.png)

* * *
### <a id="Task3"></a>Task 3 - Enter: Search Engine Optimisation
**No answer required**

* * *
### <a id="Task4"></a>Task 4 - Beepboop - Robots.txt

**4.1.** _Where would "robots.txt" be located on the domain "ablog.com"_  
Answer: <ins>ablog.com/robots.txt</ins>

**4.2.** _If a website was to have a sitemap, where would that be located?_  
Answer: <ins>/sitemap.xml</ins> [^test]  
[^test]: a .xml file is basically a text file which can be manually edited

**4.3.** _How would we only allow "Bingbot" to index the website?_  
Answer: <ins>User-agent: Bingbot</ins>

**4.4.** _How would we prevent a "Crawler" from indexing the directory "/dont-index-me/"?_  
Answer: <ins>Disallow: /dont-index-me/</ins>

**4.5.** _What is the extension of a Unix/Linux system configuration file that we might want to hide from "Crawlers"?_  
Answer: <ins>.conf</ins>

* * *
### <a id="Task5"></a>Task 5 - SiteMaps

**5.1.** _What is the typical file structure of a "Sitemap"?_  
Answer: <ins>xml</ins>  

**5.2.** _What real life example can "Sitemaps" be compared to?_  
Answer: <ins>map</ins>  

**5.3.** _What real life example can "Sitemaps" be compared to?_  
Answer: <ins>route</ins>  

* * *
### <a id="Task6"></a>Task 6 - What is Google Dorking?

**6.1.** _What would be the format used to query the site bbc.co.uk about flood defences?_  
Answer: <ins>site: bbc.co.uk flood defences</ins>  

**6.2.** _What term would you use to search by file type?_  
Answer: <ins>filetype:</ins>  

**6.3.** _What term can we use to look for login pages?_  
Answer: <ins>intitle: login</ins>  
\- note: most login pages have the 'login' word in the title of the page

* * *
### <a id="misc"></a>Additional Notes
- [Google Dorking DB Reference](https://www.exploit-db.com/google-hacking-database) - for quick reference to more google dork terms for OSINT/Recon

