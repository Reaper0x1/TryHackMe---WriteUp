# Junior Penetration Tester - WIP

## Pentesting Fundamentals 

### Task 1 - What is Penetration Testing?

> Read it
```
No answer needed
```

### Task 2 - Penetration Testing Ethics   

> You are given permission to perform a security audit on an organisation; what type of hacker would you be?
```
White Hat
```
> You attack an organisation and steal their data, what type of hacker would you be?
```
Black Hat
```
> What document defines how a penetration testing engagement should be carried out?
```
Rules of Engagement
```

### Task 3 - Penetration Testing Methodologies

> What stage of penetration testing involves using publicly available information?
```
Information Gathering
```

> If you wanted to use a framework for pentesting telecommunications, what framework would you use? Note: We're looking for the acronym here and not the full name.
```
OSSTMM
```

> What framework focuses on the testing of web applications?
```
OWASP
```

### Task 4 - Black box, White box, Grey box Penetration Testing

> You are asked to test an application but are not given access to its source code - what testing process is this?
```
Black Box
```
> You are asked to test a website, and you are given access to the source code - what testing process is this?
```
White Box
```

### Task 5 - Practical: ACME Penetration Test

> Complete the penetration test engagement against ACME's infrastructure.

```
THM{PENTEST_COMPLETE}
```

## Principles of Security

### Task 1 - Introduction
> Let's Proceed!
```
No answer needed
```

### Task 2 - The CIA Triad
> What element of the CIA triad ensures that data cannot be altered by unauthorised people?
```
Integrity
```
> What element of the CIA triad ensures that data is available?
```
Availability
```
> What element of the CIA triad ensures that data is only accessed by authorised people?
```
Confidentiality
```

### Task 3 - Principles of Privileges

> What does the acronym "PIM" stand for?
```
Privileged Identity Management
```
> What does the acronym "PAM" stand for?
```
Privileged Access Management
```
> If you wanted to manage the privileges a system access role had, what methodology would you use?
```
PAM
```
> If you wanted to create a system role that is based on a users role/responsibilities with an organisation, what methodology is this?
```
PIM
```

### Task 4 - Security Models Continued

> What is the name of the model that uses the rule "can't read up, can read down"?
```
The Bell-La Padula Model
```
> What is the name of the model that uses the rule "can read up, can't read down"?
```
The Biba Model
```
> If you were a military, what security model would you use?
```
The Bell-La Padula Model
```
> If you were a software developer, what security model would the company perhaps use?
```
The Biba Model
```

### Task 5 - Threat Modelling & Incident Response

> What model outlines "Spoofing"?
```
Stride
```
> What does the acronym "IR" stand for?
```
Incident Response
```
> You are tasked with adding some measures to an application to improve the integrity of data, what STRIDE principle is this?
```
Tampering
```
> An attacker has penetrated your organisation's security and stolen data. It is your task to return the organisation to business as usual. What incident response stage is this? 
```
Recovery
```

## Walking An Application

### Task 1 - Walking An Application

> I confirm that I have deployed the virtual machine and opened the website.
```
No answer needed
```
> Click "Start Machine" button and paste the Machine IP Address on a new tab address bar (if connected with OpenVPN) or inside the browser of your Attack Machine.


### Task 2 - Exploring The Website

> Read the above.
```
No answer needed
```

### Task 3 - Viewing The Page Source

> What is the flag from the HTML comment?
```
THM{HTML_COMMENTS_ARE_DANGEROUS}
```
> What is the flag from the secret link?
```
THM{NOT_A_SECRET_ANYMORE}
```
> What is the directory listing flag?
```
THM{INVALID_DIRECTORY_PERMISSIONS}
```
> What is the framework flag?
```
THM{KEEP_YOUR_SOFTWARE_UPDATED}
```

### Task 4 - Developer Tools - Inspector

> What is the flag behind the paywall?
```
THM{NOT_SO_HIDDEN}
```

### Task 5 - Developer Tools - Debugger

> What is the flag in the red box?
```
THM{CATCH_ME_IF_YOU_CAN}
```

### Task 6 - Developer Tools - Network

> What is the flag shown on the contact-msg network request?
```
THM{GOT_AJAX_FLAG}
```

## Walking An Application

### Task 1 - What Is Content Discovery?
> What is the Content Discovery method that begins with M?
```
Manually
```
> What is the Content Discovery method that begins with A?
```
Automated
```
> What is the Content Discovery method that begins with O?
```
OSINT
```
> Click "Start Machine" button and paste the Machine IP Address on a new tab address bar (if connected with OpenVPN) or inside the browser of your Attack Machine.

### Task 2 - Manual Discovery - Robots.txt

> What is the directory in the robots.txt that isn't allowed to be viewed by web crawlers?
```
/staff-portal
```

### Task 3 - Manual Discovery - Favicon

> What framework did the favicon belong to?
```
cgiirc
```

### Task 4 - Manual Discovery - Sitemap.xml

> What is the path of the secret area that can be found in the sitemap.xml file?
```
/s3cr3t-area
```

### Task 5 - Manual Discovery - HTTP Headers

> What is the flag value from the X-FLAG header?
```
THM{HEADER_FLAG}
```

### Task 6 - Manual Discovery - Framework Stack

> What is the flag from the framework's administration portal?
```
THM{CHANGE_DEFAULT_CREDENTIALS}
```

### Task 7 - OSINT - Google Hacking / Dorking

> What Google dork operator can be used to only show results from a particular site?
```
site:
```

### Task 8 - OSINT - Wappalyzer

> What online tool can be used to identify what technologies a website is running?
```
Wappalyzer
```

### Task 9 - OSINT - Wayback Machine

> What is the website address for the Wayback Machine?
```
https://archive.org/web/
```

### Task 10 - OSINT - Github

> What is Git?
```
version control system
```

### Task 11 - OSINT - S3 Buckets

> What URL format do Amazon S3 buckets end in?
```
.s3.amazonaws.com
```

### Task 12 - Automated Discovery

> What is the name of the directory beginning "/mo...." that was discovered?
```
/monthly
```

> What is the name of the log file that was discovered?
```
/development.log
```

## Subdomain Enumeration

### Task 1 - Brief

> What is a subdomain enumeration method beginning with B?
```
Brute Force
```

> What is a subdomain enumeration method beginning with O?
```
OSINT
```

> What is a subdomain enumeration method beginning with V?
```
Virtual Host
```
> Click "Start Machine" button and paste the Machine IP Address on a new tab address bar (if connected with OpenVPN) or inside the browser of your Attack Machine.

### Task 2 - OSINT - SSL/TLS Certificates

> What domain was logged on crt.sh at 2020-12-26?
```
store.tryhackme.com
```

### Task 3 - OSINT - Search Engine

> What is the TryHackMe subdomain beginning with B discovered using the above Google search?
```
blog.tryhackme.com
```

### Task 4 - DNS Bruteforce

> What is the first subdomain found with the dnsrecon tool?
```
api.acmeitsupport.thm
```

### Task 5 - OSINT - Sublist3r

> What is the first subdomain discovered by sublist3r?
```
web55.acmeitsupport.thm
```

### Task 5 - Virtual Host

> What is the first subdomain discovered?
```
delta
```

> What is the second subdomain discovered?
```
yellow
```

## Authentication Bypass

### Task 1 - Brief

> I have started the machine.
```
No answer needed
```
> Click "Start Machine" button.

### Task 2 - Username Enumeration

> What is the username starting with si*** ?
```
simon
```
> What is the username starting with st*** ?
```
steve
```
> What is the username starting with ro**** ?
```
robert
```

### Task 3 - Brute Force

> What is the valid username and password (format: username/password)?
```
steve/thunder
```

### Task 4 - Logic Flaw

> What is the flag from Robert's support ticket?
```
THM{AUTH_BYPASS_COMPLETE}
```

### Task 5 - Cookie Tampering

> What is the flag from changing the plain text cookie values?
```
THM{COOKIE_TAMPERING}
```
> What is the value of the md5 hash 3b2a1053e3270077456a79192070aa78 ?
```
463729
```
> What is the base64 decoded value of VEhNe0JBU0U2NF9FTkNPRElOR30= ?
```
THM{BASE64_ENCODING}
```
> Encode the following value using base64 {"id":1,"admin":true}
```
eyJpZCI6MSwiYWRtaW4iOnRydWV9
```
## IDOR
