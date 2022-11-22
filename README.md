# Honeypot Assignment

**Time spent:** **48** hours spent in total

**Objective:** Create a honeynet using MHN-Admin. Present your findings as if you were requested to give a brief report of the current state of Internet security. Assume that your audience is a current employer who is questioning why the company should allocate anymore resources to the IT security team.

### MHN-Admin Deployment (Required)

**Summary:** 
The honey pot I deployed was in the Google Cloud CLI. and used nmap with kali linux on virtual box.


<img src="MHN Admin GCloud.gif">


<img src="MHN Admin Deployment.gif">


### Dionaea Honeypot Deployment (Required)

**Summary:** Briefly in your own words, what does dionaea do?
This honey pot records or captures payloads and malware. 

<img src="Honeypot Deployment.gif">

<img src="Honeypot SSH.png">

### Database Backup (Required) 

**Summary:** What is the RDBMS that MHN-Admin uses? What information does the exported JSON file record?
MHN architecture uses a single administrator VM to deploy, manage, and collect information from the honeypots, which are deployed as separate virtual machines. The information recorded from the exported JSON file are types of malware or attacks that were captured from the honey pot.

## Notes

Challenges I faced for week 9 project was setting up and using google cloud cli because it is very confusing to use without the proper knowledge on how to use it. 

--------------------------------------------
Update:
When I was redoing the assignment to create all the gifs needed for this, the deployment did not want to work this time. When I originally did it, everything was smooth. Now nothing doesn't want to work and I am not sure why. Also the gifs not the photos would show on Github which was weird.
