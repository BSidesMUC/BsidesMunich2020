---
layout: talk
title: "OWASP API Security Top 10 – How APIs are hacked"
details: true
track: 1
accepted: true
length: 60
timeslot:
  start: 2000-01-01 13:15:00
  end: 2000-01-01 14:00:00
speakers: 
  - name: Frank Ully
    handle: 
    photo: 
    bio: "Frank Ully has studied Technical Communication at the Karlsruhe University of Applied Sciences and graduated with a diploma degree (now equivalent to a master in Communication and Media Management). While still a student, he set up the Corporate Communications and Documentation department of a Berlin-based software manufacturer and headed it for several years. Later, Frank was responsible for internal user systems and IT security. He has studied Security Management with a specialization in IT security at the Brandenburg University of Applied Sciences and was certified as an Offensive Security Certified Expert (OSCE) and Offensive Security Certified Professional (OSCP). Frank also holds the GIAC Reverse Engineering Malware (GREM) and GIAC Certified Forensic Analyst (GCFA) certifications and is a certified OSSTMM Professional Security Tester (OPST). At the end of his master studies, he began working as a penetration tester and security consultant at Oneconsult Germany in November 2017 and became a senior penetration tester and security consultant in April 2018."
recording_uri: 
slides_uri: 
---

Security is an important issue that is still often neglected when designing and developing application programming interfaces (APIs). 
The Open Web Application Security Project (OWASP) is a non-profit organization that aims to improve the security of web applications. Its most famous publication is probably the “OWASP Top 10”, a list of the ten most critical security risks in web applications.
At the end of 2019, the OWASP’s “API security” working group published the Top 10 of security risks in APIs.
Based on the “OWASP API Security Top 10”, the presentation will discuss attacks on APIs, their causes, and which measures in development help against them.
What needs to be considered when implementing mechanisms for authentication and authorization? Why should one not rely on default settings of frameworks and components? Which security gaps can arise from missing input validation? How can a protective measure such as rate limiting possibly be bypassed? 
The presentation concludes with references to further sources for a deeper examination of the topic. It is aimed at beginners and does not require previous knowledge.

### Outline

 - OWASP and the “regular” OWASP Top 10, introduction to API Security Top 10
 - For the entries in the API Security Top 10 at [OWASP API Security Top 10 2019](https://raw.githubusercontent.com/OWASP/API-Security/master/2019/en/dist/owasp-api-security-top-10.pdf)
   - Overview
   - Background / Cause
   - (Demo)
   - Issues / Security risks
   - Detecting
   - Preventing
 - Further references (Proactive Controls, ASVS, Guides)