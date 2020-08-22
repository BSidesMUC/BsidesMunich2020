---
layout: talk
title: "Pentesting Cloud Sandboxes in the wild"
details: true
track: 1
accepted: true
length: 20~30
timeslot:
  start: 2000-01-01 11:00:00
  end: 2000-01-01 11:45:00
speakers: 
  - name: Matthias Luft
    handle: uchi_mata
    photo: 
    bio: "Matthias Luft is a Principal Platform Security Engineer at Salesforce Heroku. After more than 10 years in IT Security, he is still excited about a broad range of topics (from hypervisor security to IT security management) and has presented on them on various occasions. Currently he works on container and cloud security topics."
  - name: Jan Harrie
    handle: NodyTweet
    photo: 
    bio: "Jan Harrie is freelancing as a Security Consultant. Currently, he spends the majority of his research time on containers and their run-time environments. If he is not digging into containers, the daily business consists of securing container environments, security risk assessments, and conceptional topics. In the past he worked as penetration tester, consultant and spend a while in academia."
recording_uri: 
slides_uri: 
---

Building on last year’s explanation of container workings under the hood ([F***ing Containers - how do they work?](https://2019.bsidesmunich.org/talks/01-03_Fucking-Containers/)), we explain several techniques for breaking out of misconfigured containers/container hosts.
We will discuss the most common misconfigurations (such as extensive container privileges, exposed network services, mounted sockets, internal cluster privileges) and how to test for them.
For each discussed attack vector, we will show how it can be automated (and integrated into build pipelines) using a tool of choice.
Finally, a comparison of the well known container execution platforms (AWS, Azure, fly.io, GCP, Heroku) will be presented.


### Outline

  - Short Container Re-Cap (make sure to be familiar with [F***ing Containers - how do they work?](https://2019.bsidesmunich.org/talks/01-03_Fucking-Containers/))
  - Attack Vectors
    - Container Privileges
    - Network Services (Generic, Cloud, Cluster)
    - Cluster Privileges
    - Sockets
  - Cloud Platform comparison
  - Testing how-to with [botb](https://github.com/brompwnie/botb) and [amicontained](https://github.com/genuinetools/amicontained/)
  - Mitigations
  - Conclusions
